# WHIMC-Habitat-Chatbot-ML
Notebooks for creating models for habitat and chatbot MLs

## agent_chatbot
Deprecated not used with MC PA anymore

## habitat_ml
### Notebooks
| Name | Description |
|---|---|
| Block_Preprocessing.ipynb | Notebook to drop highly correlated columns and/or normalize/standardize the data. |
| code_labeler.ipynb | Notebook to convert researcher codes to labels used by the AI. |
| DBBlockCounter.ipynb | Notebook to count number of blocks used by teams using a .db file and a list of builders on each team. |
| Habitat_block_data_collector.ipynb | Notebook to count number of blocks used by teams using the database and a list of builders on each team. |
| Habitat_MLP_Random_Search_Cross_Validation.ipynb | Notebook to optimize MLP using random search with different number of nodes and layers. |
| Habitat_MultiInput_MixedData.ipynb | Notebook to run CV on image and categorical data. |

Format for builder csv used in notebooks above
| id | world | builder1 | builder2 | builder3 | builder4 | builder5 |

