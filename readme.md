# Machine Translation

## Hindi to English

This repository contains the codes for the machine translation .

Data set used :

IIT Bombay hindi corpora



The BLUE score achieved : 8.991

Model used :

A very simple seq2seq model using BiLSTM encoder decoder with attention.
This is the baseline model to be developed later.


Machine used for training : DGX 32 GB GPU 

trained models can be found in the pretrained folder

## Some Examples of translation

जबकि कांग्रेस इस बात पर सहमत नहीं हो सकी कि आगे की कार्यवाही करनी है या नहीं, बहुत से राज्य प्रतीक्षा नहीं कर रहे।

original : And while Congress can't agree on whether to proceed, several states are not waiting.

predict : While the Congress could not agree to further action or not, there is no wait for many of the State.


पुलिस ने अदालत में मौत की जांच की अंतिम रिपोर्ट सौंप दी है।

original :The police have filed the final investigation report with the court.

predicted:The police have assigned the final report of death in the court.


देश में इतने अखबार और चैनल हैं।

original :The country has so many newspapers and news channels.

predicted : There are many newspapers and channels in the country.


PS : I have just added some good looking lines. The entire translation can be found as the outputs directory .This is the translation of the test corpus in the  dataset.













## TO DO :

1. Develop a model using transformer
2. Develop a model using pretrained model (BERT)
There is a huge monolingual corpus in the dataset 
