# SGParrot_2021
### 2021-1학기에 진행했던 mini competition 코드
최종 결과물과 코드 설명은 ```0408_logfile.ipynb```, ```output_ensemble.ipynb``` 및 ```toxic_final.pdf``` 파일 참고

![toxic_final2](https://user-images.githubusercontent.com/80621384/141649778-151c00a0-019a-4fa4-b93d-22ff799d5269.png)

## data set
[Kaggle Competition](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge)

train/test/sample_submission datasets from Kaggle original competition

## try-outs
**1. Preprocessing**
 - removing stopwords
 - text augmentation
 - cleaning with re module
 - lemmatization

**2. Tokenizing**
 - sentencepiece

**3. pretrained word embedding**
 - GloVe

## model
 - CNN (Conv1D)
 - Bidirectional LSTM
 - CNN + GRU
 - NBSVM (Naive Bayes SVM)

++ with emsembling outputs

## takeaway notes
![notes](https://user-images.githubusercontent.com/80621384/141650122-ee4e1a07-e862-41c0-812c-ceb8ab606eb4.png)


## prize
총 5팀 중 2위
