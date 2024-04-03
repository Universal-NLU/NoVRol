# NoVRol

This repository contains the Norwegian verb role lexicon described in Henrik Torgersen, Erlend Øyvindssøn Ravnanger, Lars Hellan and Dag Haug, "NoVRol: A semantic role lexicon of Norwegian verbs", DMR workshop 2024. The following is a brief presentation of the data. For more details, consult the publication.

The data are in a csv file with the following columns: `lemma`, `Norval_frame`, `UD_frame`, `example`, `theta1`, `theta2`, `theta3`, `theta4`. `lemma` and `Norval_frame` are taken from the Norval valency lexicon described in Lars Hellan, "A Valence Catalogue for Norwegian", in R. Loukanova (ed) _Natural Language Processing in Artificial Intelligence_, Springer 2021 pp. 49--104. NorVal can be [downloaded here](https://github.com/Regdili-NTNU/NorSource/tree/master/NorVal_files). `UD_frame` contains the grammatical functions of the arguments specified by the NorVal frame, given in the style of [Universal Dependencies](https://universaldependencies.org/). The grammatical functions are separated with hyphens. `example` contains an example sentence with the specified frame. `theta1`, `theta2`, `theta3`, `theta4` specifies the thematic roles of the frame arguments, given in the same order as in the UD frame.

The grammatical roles are drawn from the following inventory, mostly based on the English VerbNet inventory, with some minor modifications described in the paper.

|               |               |               |            |
|---------------|---------------|---------------|------------|   
| adjective     | adverb        | agent         | asset      |        
| attribute     | beneficiary   | cause         | co-agent   |     
| co-patient    | co-theme      | destination   | direction  |    
| duration      | experiencer   | final_time    | formal     |   
| goal          | initial_time  | instrument    | location   |  
| material      | null-role     | orientation   | patient    | 
| patient-theme | pivot         | product       | recipient  |
| result        | source        | stimulus      | theme      |
| time          | topic         | trajectory    | value      |

The data are available under the licence [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)