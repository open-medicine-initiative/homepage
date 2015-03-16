## A guide for making choices...

> [...] any system that produces individualised recommendations as output or has the effect of guiding users in a personalized way to interesting or useful objects in a large space of possible options.
(Burke (2002), Hybrid recommender systems:survey and experiments)

A recommender system acts as a a guide for people when they are confronted with large sets of options to choose from. In the context of medicine it can guide patients in their search for case-specific medical information, e.g. potential causes for symptoms or benefits & risks of therapeutic means for their condition. It works based on comparison of [medical profiles](Medical-Profiles), using different [notions of similarity](How-it-works#distance-metrics) as a primary heuristic to identify relevant medical information.

## Relying on collective knowledge...

> Social information filtering essentially automates the process of "word-of-mouth" recommendations...
(Shardanand and Maes (1995), Social information filtering.algorithm for automatic word-of-mouth, Proceedings of the conference of Human Factors in Computing Systems)
 
The openMediAid recommender system assumes that what has worked for some will work for others who are in some ways similar. What has explained the condition of one may explain the condition of another.

> Recommender systems use the opinions of a community of users to help individuals in that community to more effectively identify content of interest from a potentially overwhelming set of choices.
(Herlocker et al.(2004), Evaluating collaborative filtering recommender systems)

### Generating recommendations
Varying with the type of problem, the user of a recommender system has different needs that influence the way recommendations are generated. The fundamental approach of any recommender system, however, stays the same: Find useful pieces of information **based on a utility function** that models the user's needs. This can be done based on different criteria and using different techniques.



**Collaborative recommendation**, in which the user is recommended items that people with similar tastes and preferences liked in the past. Collaborative recommendation (or collaborative filtering) system predict a user's interest in new items based on the recommendations of other people with similar interests.

**Knowledge-based recommendation**, which suggests items based on logical inferences about user preferences. A knowledge representation (e.g. rules) about how an item meets a particular user need is necessary.

In the context of medical information processing it will be primarily the collaborative and knowledge-based approaches that are used to generate medical recommendations. [WIP]

For the sake of completeness:

**Utility-based recommendation**, which makes suggestions based on computation of the utility of each item for a user, for whom a utility function has to be stored.

**Content-based recommendation**, in which the user is recommended items similar to the ones he has preferred in the past. Content-based recommendation systems analyse a set of items and/or description previously preferred by a user, and build a model of user interests based on features of these items.

# Machine Learning

[WIP]. Please refer to the Wikipedia article about [machine learning](http://en.wikipedia.org/wiki/Machine_learning).

### Supervised learning
### Clustering
### Principal Component Analysis
### Feature vectors and projections into euclidean space

http://www.siam.org/meetings/sdm12/wang_sun_part1.pdf
http://www.siam.org/meetings/sdm12/wang_sun_part2.pdf
http://www.cs.umb.edu/~rickb/diss/rickDissertation.pdf