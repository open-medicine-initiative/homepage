A medical profile is a container for health information that describes a medical case. It can be owned by a real patient or a virtual agent of the system. It can be used in search queries for similar cases or other relevant medical information. It can represent medical knowledge about a common case of a particular disease or an aggregation of real cases. There are different types of profiles used to represent different types of knowledge in the system. However, they all share a [common data structure](Medical-Data-Model) to make them interoperable. 

<a name="archetype-profiles"></a>
### Archetype profiles
A medical condition can be characterized by the symptoms it causes and the way these symptoms develop over time (clinical representation & time course).  
The purpose of archetype profiles is to **capture common variations** of those developments - a blue print, identifying common cases of a specific diseases. Archetype profiles can be matched with real patient profiles in order to find information about possible causes for symptoms (support for differential diagnosis) or standard methods of treatment.

<a name="clustered-profiles"></a>
### Clustered profiles
Clustered profiles represent average cases of similar patients extracted by machine learning algorithms. They **extend archetype profiles with more variations**, eventually leading to the formation of more specific subclasses. It should be expected that some of the them will overlap significantly with existing archetype profiles which can be interpreted as a sort of **verification of the archetype profiles** correctness. Clustered profiles can also **represent combinations of diseases** that commonly appear together.

<a name="patient-profiles"></a>
### Patient profiles
The major part of medical data will be real patient data - maintained by the users themselves as their own personal health record. Patient profiles pour in the **experience and expertise of patients** and make it available to the community.  

They contribute to the richness and diversity of the platforms medical knowledge and **extend the common medical facts** with what might not have been verified by empirical research. Patient profiles bring in the creativity of people and allow the community to [measure and verify what works](FAQ#focus-on-what-helps) and what doesn't.
 
The automated formation of networks of similar profiles  allows every user to participate in the knowledge exchange of groups of related patients (=> [medical peer groups](Features#medical-peer-groups)). 