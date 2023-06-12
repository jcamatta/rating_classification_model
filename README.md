# HUGGING FACE FINE TUNNED BERT MODEL WITH GOOGLE REVIEWS FROM ALASKA

As the pretrained model we use BERT: **bert-base-uncased**

The alaska dataset has a size of 56137. The alaska dataset was previous pre-processed using HuggingFace's datasets library. The specific code can be found in the same folder that we are.

Train size = 51033 (80%) | Validation size = 1020 (2%) | Test size = 4084 (8%)

Batch size = 8 | epochs = 3

For the validation dataset we got a 88% of *accuracy* and 81% for *f1-score*.

For the test dataset we got 88% of *accuracy* and 80% for *f1-score*.

The fine-tunning proccess was entirely made by transformes and datasets libraries. 

It took 1 hour to complete using google colab's GPU.
