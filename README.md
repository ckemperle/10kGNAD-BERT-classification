# 10kGNAD-BERT-classification

I classified the [Ten Thousand German News Articel Dataset](https://ofai.github.io/million-post-corpus/) with two BERT transformer text classifier ([BERT Adamax](https://github.com/ckemperle/10kGNAD-BERT-classification/blob/main/BERT_512_adamax.ipynb), [BERT Adam](https://github.com/ckemperle/10kGNAD-BERT-classification/blob/main/BERT_512.ipynb)) and one [SVM classifier](https://github.com/ckemperle/10kGNAD-BERT-classification/blob/main/SVM.ipynb) which was created from [tblock](https://github.com/tblock/thesis-data). The two BERT classifier got an accuracy of 0.80 and 0.76, where the SVM classifier got to an accuracy of 0.885 respectively.

## BERT Adamax
BERT Adamax was trained for four epochs and a batch size of 32 with:
![BERT Adamax](https://user-images.githubusercontent.com/39309601/130027169-62018dbd-f5f1-4e33-a45b-c26898df4963.png)
![BERT Adamax Confusion Matrix](https://user-images.githubusercontent.com/39309601/130027241-b387eaf1-1b16-41f6-bc75-acaa80765e14.png)

## BERT Adam
BERT Adam was trained for four epochs and a batch size of 32 with:
![BERT Adam](https://user-images.githubusercontent.com/39309601/130027317-3476b4db-4881-495a-8b5f-005117d61ac5.png)
![BERT Adam Confusion Matrix](https://user-images.githubusercontent.com/39309601/130027386-77f10470-a014-4233-a2b0-b52e926d1df2.png)

## SVM
![SVM Confusion Matrix](https://user-images.githubusercontent.com/39309601/130027469-01d18ecb-e24a-4773-8fe1-bee376e3b5d1.png)
