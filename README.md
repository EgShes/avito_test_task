# Solution of test task for summer internship in Avito
The task was to train a model to predict Avito adverticement category by it's title, description and price.

## Trained models
1. Fasttext:
Very fast training and and good perfomance (~ 0.86 on validation set);
1. ELMO + CNN:
Super slow inference because of ELMO calculation of word embeddings. Was trained for 3 epochs (~ 3 hours for every epoch) and stopped. Not the best performance (~ 0.82) and tremendously slow inference;
1. ULMFiT:
The best performance (~ 0.87) and good speed of inference.

## Test predictions
Test predictions for test set are in results folder.

P.S.
1. I realized that I forget to create test set besides validation set from training set when I've already were training the second and third model. So I didn't restart;
1. Don't see at the order of executing of cells. It's messed because I tried to make notebooks look good;
1. There are two notebooks because the second and third models were trained simultaneously.
