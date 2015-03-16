OpenMediAid is a crowdsourced, **non-profit**, open medicine platform built to support patients in their search for medical information. It connects patients with similar conditions into support groups wherein each individual can benefit from the experiences and insights of other members.

OpenMediAid is built as a **data-driven social network with** databases of medical knowledge and **tools for** visualization and statistical **analysis of medical data**. 

It aims to support a **collaborative** approach to medical decision making based on evidence: 
Structured **data collection and knowledge transfer** within a large community increases information transparency and **empowers patients** to take qualified medical decisions.

[![openmediaid](https://github.com/open-medicine-initiative/openMediAid/wiki/resources/profile-matching-process.png)](https://github.com/open-medicine-initiative/openMediAid/wiki/resources/profile-matching-process.png)

Patients manage and share their medical profiles online (1). Supervised machines match patients based on their medical profiles (2) to create support groups (a), case-specific medical reports (b) and lots useful of statistics (c).

***
_Patients use openMediAid to:_
* Collect, visualize and search all their [medical data](Features#medical-profile) in one place
* Find, connect with and [learn from patients](Features#medical-peer-groups) who are like them
* Explore statistics on symptoms, diseases and treatments
* Learn about all treatment options relevant to their condition(s)

***
| We need your help!  |
|:--------------:|
|_The openMediAid project is still in early planning and prototyping phase_|
|Read about the **[project status](#project-planning)** and how to **[contribute](#contribute)**.|

# Missed opportunities in health care
The health care system suffers from various structural deficits for which solutions need to be found.
It relies too much on a small group of experts, expensive medical infrastructure and profit-oriented companies to provide medical services to a continuously growing number of people. More specifically:

**Conflict of interest**<br />
Profit-oriented markets are often unsuitable environments for creating simple and cost efficient medical solutions. From a shareholders point of view it is more attractive to make a patient become a long-term consumer of medical services/products instead of a one-time customer - after all, life-long treatment of symptoms generates constant revenue.

Financial interests have considerable influence on the quality and outcome of medical research.\[[1](#references)\] 

For-Profit health service/product providers also tend to have lower interest in the transparency of health care markets \[[2](#references)\] because well informed patients are likely to adapt a more defensive consumption strategy. 

**Lack of information**<br />
Unfortunately, most of the existing medical knowledge bases are commercial and protected by pay-walls. Too little effort is made to integrate the various sources of information, leading to the typical problems of *information silos*. Publicly available medical information in the internet is mostly unstructured, opinionated, difficult to verify and rarely references empirical data.

**Lack of trust**<br />
The lack of high quality medical information is intensified by the strict data protection policies that make it difficult for doctors, hospitals and other institutions to share patient's medical data. These policies are a consequence of the growing distrust towards industries and state institutions to use data for the benefit of people instead of money making or surveillance.

**Lack of time**<br />
Many doctors lament that they do not have sufficient time to spend on a single patient and recognize the implications of this constant time pressure:<br />
There is not enough room for discussions, explanations or cooperative decision making. Patients regularly don't feel taken seriously, leave without being well informed, are uncertain about what decision to take or whether to follow their doctor's medical advice. Even worse, humans err when under pressure and given medical advice might actually be wrong, misleading or excluding viable alternatives. 
 
**The patient - an underestimated resource**<br />
Another major problem is that the patient is not recognized as an active agent in her/his recovery. Patients consult doctors, undergo clinical examinations and treatments and research for relevant medical information.<br/>
Many patients become skilled and knowledgeable about the different aspects of their condition and usually end up with an extensive record of medical data. Their accumulated knowledge and medical records are invaluable sources of information for other people with similar health problems. It may save them time, money and suffering if appropriate diagnosis or treatment can be found more quickly.

After all, **medicine is an empirical science** and as such medical decisions should be based on knowledge and evidence generated from patient data.

*If only all this knowledge and data were freely available...*

# Crowdsourcing an open data solution
> **...under the right circumstances, groups are remarkably intelligent, and are often smarter than the smartest people in them’... wisdom of crowds is derived not from averaging solutions, but from aggregating them.** <br />
> \- _Surowiecki, J. (2004) The Wisdom of Crowds_

The idea of openMediAid is to __[crowdsource](Crowdsourcing)__ the development, operation and evolution of a non-profit, __[Medical Decision Support System](Glossary#mdss)__:

An open medicine platform built on models of expert medical knowledge, open medical data and machine learning. It will be transparent about its data and algorithms, empower patients to be active agents in medical decision making and knowledge building, save research time for both patients and doctors, be trustworthy with a non-profit community that has not conflict of interest.

**Patients** anonymously share their medical data and document their progress, personal insights and expertise on their condition.<br />
**Doctors** share their medical expertise, peer-review data and supervise computer-aided knowledge discovery.<br />
**Together** they create a software platform able to provide case-specific medical information and advice backed by data. They create community able to help patients to be aware of all the options and pieces of information relevant to their medical condition.

Moreover, openMediAid is powered by **people AND machines**.  
Supervised learning algorithms work tirelessly to filter, classify and prepare information from the pool of medical profiles. Incoming medical data is continuously incorporated into the case-specific clusters and statistics on symptoms, diseases, treatments and clinical tests.  
The algorithms also connect patients with similar profiles to form peer groups wherein relevant discoveries of individual patients are automatically distributed to all their peers.

> **We believe in the following core values and principles as the foundation for its success.**

|![Unlocked](wiki/images/crowd.png)|![Gift economy](wiki/images/gift.png)|
|:-----------:|:-----------:|
| **collaboration** | **gift economy** |
| Medical knowledge building and decision making require analysis and interpretation of complex data. We rely on lots of [collaborating brains](http://en.wikipedia.org/wiki/Wisdom_of_the_crowd) to build databases of medical knowledge and learning algorithms to make use of all documented patient experience. | We want to build free, non-profit medical information services with a community of volunteers. We found the project on trust and a culture of sharing and caring instead of ~~financial revenues~~, ~~customer success~~ and ~~shareholder value~~. |

|![Open Data](wiki/images/unlocked.png)|![OSS](wiki/images/oss.png)|
|:-----------:|:-----------:|
| **open data** | **open source**|
| Medical knowledge is meant to help people, its access must therefore be unrestricted. Medical decisions need to be based on evidence generated from patient data. All involved data needs to be freely available for the sake of transparency and to make the best out of all opportunities. | Open source code development allows anybody to contribute ideas and work. Code is designed, discussed, tested and revised by many people. Everybody can see what the code is doing, everybody can propose modifications. |

|![Data cube](wiki/images/datacube.png)|![Feedback loop](wiki/images/loop.png)|
|:-----------:|:-----------:|
| **big-data and cloud technology** | **continuous feedback** |
| We want to combine powerful data processing technologies (NoSql databases, map reduce, machine learning) with cloud computing to create an open ecosystem for the evolution of medical data and algorithms. | We embrace change and support incremental improvement of collected medical knowledge with an interactive system that learns from its community and incoming data. |

|Read more about...|
|:---------------:| 
| [How it works](How-it-works) \| [Recommender system](Recommender-System) \| [eHealth](http://en.wikipedia.org/wiki/EHealth) \| [Patient Participation](http://en.wikipedia.org/wiki/Patient_participation) |

<a name="project-planning"></a>
# Project plan & status
The openMediAid project is a vision under active development but still in an early stage - all parts, including this concept, are work in progress (WIP).  
Project planning and code development is done in public spaces so that everybody can see what is happening and get involved. There is a rough project plan consisting of three phases:

**(1) Bootstrapping Phase**  
Bootstrapping the project means to summon the basic infrastructure (team, community, IT and other resources) and to design a first product specification. We are founding the non-profit [Open Medicine Initiative](http://www.open-medicine-initiative.org) - the official legal entity to coordinate the project. We will [grow our team](#join-the-force) and a community of supporters, build IT infrastructure, campaign for financial support (mainly via crowd-funding), dive into feature specification, design data models, seed data and build an [initial prototype](https://github.com/open-medicine-initiative/openMediAid/milestones/1.0.0).

**(2) Platform Development Phase**  
As soon as we have crowd-funded sufficient financial support we can focus more resources on the development of algorithms and user interface, crowd-source data collection and integration of all parts into a usable online platform. We will work with short development cycles and continuous deployment of our current code base to regularly gather feedback from the community.

**(3) Public Beta Phase**  
Eventually, we will have a platform and backend of data and algorithms that is stable enough to be used and tested by a larger community of patients and doctors. The coordination schemes for this phase need to be designed with experiences gathered from the first two phases. There will be specific needs arising during the platform development that are currently unpredictable.

**Repositories**<br />
We are managing the different aspects of the project in distinct repositories.

| Repository | Description |
|:-----|:-----|
|[Development](https://github.com/open-medicine-initiative/openMediAid/issues)| Code development, features and technology|
|[Medical landscape](https://github.com/open-medicine-initiative/scratchpad/issues)|Research on medical data, services, health providers|
|[Open Medicine Initiative](https://github.com/open-medicine-initiative/org)|Documents, financial statements and other stuff related to the organizations legal entity|

<a name="contribute"></a>
# Contribute
> **I not only use all the brains that I have, but all that I can borrow.**<br />
> \- _Woodrow Wilson_

openMediAid is a crowd-sourced project - it is **built with** the support of **a community of volunteers**. 
<a name="join-the-force"></a>
We need people willing to continuously support the project. We are especially looking for expertise in
* [Diagnosis & Treatment of Disease](https://trello.com/c/hEJSd4Ta)
* [Data Science](https://trello.com/c/VZafmORA)
* [Community Management](https://trello.com/c/YnV0dlWm/)
* [Developer operations](https://trello.com/c/SiM2NUsV/)
* [JavaScript Frontend Development](https://trello.com/c/1SR8zdxi/)
* [JavaScript Backend Development](https://trello.com/c/F23JGan5/)

_Note: We are planning to crowd-fund salaries for all major positions but until we are, all support is purely volunteer._
___
If you can not offer continuous support but still want to help out, check out our **[list of contributions](https://trello.com/b/I3o3m2Ix).** You can also become a member of our **board of advisors**.

If you are a developer, please check out our [issue list](https://github.com/open-medicine-initiative/openMediAid/labels/help-wanted).

You know a great site that offers medical information or services and would like to see some of its features in openMediAid? Submit a feature request [here](https://github.com/open-medicine-initiative/openMediAid/issues).
___

<a name="contact"></a>
# Contact
Currently, the project is based in Berlin - in an amazing, ecosocial co-working space called [Thinkfarm](http://thinkfarm.de/). You can come for a visit almost any time.

If you want to get in touch write an email to `contact (at) openmediaid (dot) org`

You can also visit our [Facebook page](https://www.facebook.com/open.medicine.initiative)

<a name="license"></a>
# License
An appropriate license has not yet been selected. It will most likely be a creative commons license that prohibits use in commercial ways but does not restrict use otherwise ([CC-BY-SA](https://creativecommons.org/licenses/by-sa/3.0/)).

<a name="references"></a>
# Footnotes
[1] Pharma industries, for example, have been publicly criticized for [spending more money on marketing than on R&D](http://www.sciencedaily.com/releases/2008/01/080105140107.htm)  
[2] [Pharmaceutical industry sponsorship and research outcome and quality: systematic review](http://www.bmj.com/content/326/7400/1167)  
> Conclusion: Systematic bias favours products which are made by the company funding the research [...].

[3] [The scandal of poor medical research](The scandal of poor medical research)  
[4] [Reporting bias of medical research](http://www.biomedcentral.com/content/pdf/1745-6215-11-37.pdf)  
[5] [Number needed to treat](http://www.wired.com/2014/10/number-needed-to-treat)