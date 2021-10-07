# Kakao-Shopping-Classification

![image](https://user-images.githubusercontent.com/87184009/127741874-88c11a0a-51d5-4c79-829e-b88066684140.png)

## Introduction

In this project, I classified millions of shopping products into 2,000 categories. Each product has a product name, brand name, model name, price, and image information. Product name, brand name, and model name are written in Korean. I used NLP techniques and pattern matching to cluster similar product, brand, and model names. The proper classification of shopping products is related to our real life, so I thought the experience of working on this project would be helpful when I work in the industry.

## Research Method

1. Print product name, brand name, and model name to get an idea of how to cluster the names.
2. Recognized that we need additional preprocessing steps to do embedding.
3. Found out that pattern matching could be an efficient process to preprocess the words in the Korean product names.
4. Combined state-of-the-art NLP techniques and pattern matching in the preprocessing step.
5. Build a neural network model consisting of two hidden layers and a softmax function.
6. Tuned hyperparameters in both preprocessing and training steps.

## Result

Test Score : 1.11923 \
Implemented the most accurate shopping product classification model among 50 students.
<br/><br/>
![image](https://user-images.githubusercontent.com/87184009/127637326-58a6fe34-25e4-4540-b380-63dde355f891.png)

## References

KAIST CoE202: Fundamentals of Artificial Intelligence \
http://kalman.kaist.ac.kr/coe202/

Kakao Shopping Product Classification Contest\
https://arena.kakao.com/c/5 \
https://github.com/kakao-arena/shopping-classification

Unfortunately, the final version of preprocess.ipynb, train.ipynb was lost and the initial version of the code was uploaded.
