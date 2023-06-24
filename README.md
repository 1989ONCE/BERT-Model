# BERT-Model
Sentiment Analysis implement by transformers (Using Pytorch)

### Datasets:
  - load_dataset-> imdb movie comments
  - split into three parts: train, validation, test
  - label def: 
    - 0 for negative comment
    - 1 for positive comment
### BERT MODEL(options)
-> bert-base-uncased: 93% </br>
-> bert-base-cased: 87.4% </br>
-> distilbert-base-uncased </br>
-> RoberTa

### Best Result of Test Accuracy
Test Accuracy = 0.93

### Prediction Result for test data
<img width="323" alt="image" src="https://user-images.githubusercontent.com/92381825/235470773-6269960d-6656-468d-ba7b-fedd03d69c52.png">

### Random Test for random sentence
Result was Correct, "This movie doesn't attract me" IS A negative comment. </br>
<img width="380" alt="image" src="https://user-images.githubusercontent.com/92381825/235471184-d52e2fb2-2545-412b-b076-dbd12516c41a.png">

