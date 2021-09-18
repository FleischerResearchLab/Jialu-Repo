
The foodNER.ipynb notebook contains a name entity recognition model to extract food item from food logs. It also contains code to generate wordcloud for participants.

With foodNER notebook, you can train your own name entity recognition model with your own data and training template.

# Getting Started

To train a new name-entity recognition model, we need to have a dataset containing words of that entity. We also need to design a template for training the NER model containing sentences or short phrases such as "James ate {} and {}" or "4 slices of {}" where {} were to be replaced with random entity words during the training process.

After training, the NER model would be able to extract the specified entity from any sentence or phrase.



# Acknowledgement

Scripts to extract food entities are partly from Isaac Aderogba at https://deepnote.com/@isaac-aderogba/Spacy-Food-Entities-LMLRnMOsQyGIUwvPLvVlsw



