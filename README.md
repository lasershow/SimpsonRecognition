# SimpsonRecognition

Training a Convolutional Neural Network to recognize The Simpson TV Show characters using Keras (TensorFlow backend).
To have more detailed explanations, see the blog articles on Medium [Part 1](https://medium.com/alex-attia-blog/the-simpsons-character-recognition-using-keras-d8e1796eae36) and [Part 2](https://medium.com/alex-attia-blog/the-simpsons-characters-recognition-and-detection-part-2-c44f9d5abf37). If you like it, don't hesitate to recommend it (as for the dataset on [Kaggle](https://www.kaggle.com/alexattia/the-simpsons-characters-dataset))

## データ・セットをKaggleからダウンロードする

[Kaggle](https://www.kaggle.com/alexattia/the-simpsons-characters-dataset)

### 解凍

the-simpsons-characters-dataset.zipを解凍し、その中のsimpsons_dataset.zipを解凍する

### データ・セットを格納する
simpsons_datasetをプロジェクトフォルダ配下に格納する

`SimpsonRecognition/simpsons_dataset`

## 学習
`train_frcnn.py -p annotation.txt`

![Lisa picture](https://github.com/alexattia/SimpsonRecognition/blob/master/pics/mapple_lisa.png)
