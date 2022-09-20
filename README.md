# Bark_Classification
Bark type classification for the TMLC Fellowship project

In this project I'm using the BarkVN dataset from kaggle. I have decided to go with a hybrid cnn and XGBost model to solve this problem of tree bark classification. My hybrid model uses a Resnet50 as a feature extractor with a XGBoost layer instead of the final softmax layer to give better outputs.
