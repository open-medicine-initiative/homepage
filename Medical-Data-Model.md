Descriptions of medical concepts may very from person to person (even among experts) and are different depending on language and level of expertise. To rule out those inconsistencies in medical descriptions and to make medical profiles comparable across language and cultural borders **a single representation of knowledge** is necessary.

The medical data model provides this building block for descriptions of medical conditions of patients, epidemiology and pathology of diseases as well as other diagnostic knowledge.

It is **a formalization of the medical domain** containing aspects of human physiology, body functions, symptoms and all the meaningful relations between them. 

It is used to give structure to patients medical data and is the basis for comparison and classification of different medical profiles.

[![Full model](resources/mdm-full.png)](resources/mdm-full.png)

> Note: This diagram is a conceptual representation that is neither complete nor following an exact notation or formalism.

<a name="medical-language"></a>
##Medical Language
The medical language aspect of the data model provides the system with all the parts and concepts necessary to accurately represent descriptions of medical conditions: symptoms, diseases, treatments etc. It is a decomposition of medical terminology into atomic, reusable, descriptive units - the Medical Classifier. Any description of medical facts is created by composition of a set of medical classifiers. 

| Textual description | Composition into classifiers |
|-----|------|
| severe regular pain in right hip | pain && hip(right) && intensity(8/10) && frequency(regular)|
| mild swelling in knees half an hour every morning | swelling && knee(both) && duration (30min) && frequency(regular) && frequency (morning) |

The medical language contains classifiers for human physiology, scales for quantification and concepts for describing other features of the physical world.  

[![ML model](resources/mdm-ml.png)](resources/mdm-ml.png)

<a name="core-model"></a>
## The core model
[![Core model](resources/mdm-core.png)](resources/mdm-core.png)

[WIP]
### Medical Finding
Description of any detectable medical fact about a patient - a perceived symptom or result of clinical exam, laboratory measurement etc. Anything relevant to describe health situation of a patient. Many facts about the human body can be measured using laboratory tests or clinical examinations. Examples:  
+ blood glucose level of X mmol/L
+ antibody of streptococcus
+ erythrocite sedimentation rate


