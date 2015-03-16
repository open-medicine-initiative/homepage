<a name="data-collection"></a>
## Data collection
Large sets of real patient data is a prerequisite for the machine learning to function properly. The quality of clustered profiles depends on the size of the samples used to generate the profile. 

Sources for patient profiles:
+ Patients themselves. Will take a while until patients submit quality data.
+ Digitize existing (paper based) patient profiles with groups of volunteers
  + designed as part of a course (additional seminar) in university of medicine
  + organized data collection camps
  + establishing helpdesks for patients to have their record digitized

Starting without patient profiles:
Archetype profiles can be defined based on existing literature (books of medical knowledge), (meta-)studies and databases.

<a name="data-quality"></a>
## Data quality
Data quality will be a primary issue in running an open medical information platform where everybody can enter data and as such has an influence on the functions working with that data. To protect against fraud or data corruption it should be ensured that
* a medical profile belongs to a real person and only one profile per person is available
* different methods of profile verification are available (sms, post ident, helpdesks)
* dynamic verification scores (secret) influence the profiles impact
* new, unverified profiles are not considered in clustering
* there is a continuous peer-review process of profiles and other parts of the model
* bots are be kept-out of the system
* automatic systems detect suspicious activity (secret)

Similar to the elaborate permission system used by the [stackexchange](http://stackexchange.com/) communities, a system of control is established using different roles that a community member can fulfil

Other factors that influence data quality: 
+ Mapping of natural language based descriptions with medical classifiers need to be accurate and intuitive
+  Excellent editor/wizard to guide anamnesis
+  Internationalization and handling of synonyms as well as ambiguous terms
+ Striving towards complete profiles
+ Flexible data model that can evolve with growing data and requirements

<a name="ui"></a>
## User Interface
Providing excellent guidance during this process is essential for the correct functioning of the profile matching. Flawed descriptions of medical cases can not produce reliable matches with other profiles and can generate misleading information. 

## Supervision and Evolution
The available medical knowledge needs to continuously evolve and improve in quality. It is very unlikely that all the models, algorithms and other parts of the system will produce the expected results right from the beginning. Instead of trying to create a perfect system from scratch it is much more promising to build the possibility for evolution into its core. People need to be able to interact with it in order to add new information and adjust existing knowledge. Only if the system can learn from people may it be able to teach them.

Smart technology alone will not solve the problem of providing medical advice. As important as the right technology is a healthy community process that allows people to participate in different roles - patients, general doctors, neurologists, software engineers etc. - providing distinct types of information and supervising different parts of the system.

Information exchange and collaboration must be transparent such that everybody can get involved and understand how decisions have made. A community moderation system based on trust and reputation inspired by [stackexchange.com](http://blog.stackoverflow.com/2009/05/a-theory-of-moderation/) and wikipedia.org will help coordinate the efforts of larger groups of people.
