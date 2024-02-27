# Document classification model for Sustainable Development goals 

## Prepare dataset.

You can use Scival to obtain Scopus EIDs of tagged articles. Then, you should get the title, abstract and keywords of the articles using these EIDs. You can make requests to Scopus API using the pybliometrics library.

## Train modal

I used Google BERT's base model to create the model. I improved my model by fine-tuning this pretrained model.

## Evaluate modal

I achieved high accuracy with the model I trained. You can see the model results below.


<img width="508" alt="MicrosoftTeams-image" src="https://github.com/ecagataydogan/sdg-classification-model/assets/101594855/e67f7c59-8210-4362-ba91-eb08763c953a">
