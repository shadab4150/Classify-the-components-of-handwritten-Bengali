# Classify-the-components-of-handwritten-Bengali

Bengali.AI Handwritten Grapheme Classification

Bengali is the 5th most spoken language in the world with hundreds of million of speakers. It’s the official language of Bangladesh and the second most spoken language in India. Considering its reach, there’s significant business and educational interest in developing AI that can optically recognize images of the language handwritten.

Bangladesh-based non-profit Bengali.AI is focused on helping to solve this problem. They build and release crowdsourced, metadata-rich datasets and open source them through research competitions.

* **Classify three constituent elements in the image: grapheme root, vowel diacritics, and consonant diacritics.**

### Why Grapheme

![kd](https://i.ibb.co/zXtyYTg/graph.jpg)


![kd](https://i.ibb.co/vQHj6RR/grapheme.jpg)

* Project [**Notebook**](https://github.com/shadab4150/Classify-the-components-of-handwritten-Bengali/blob/master/Grapheme_Bengali_Letter_detection.ipynb)

* Dataset was is parquet file which has to be converted to image:

* In this I have build CNN model which separately classifies three constituent elements in the image: grapheme root, vowel diacritics, and consonant diacritics.

![kd](https://i.ibb.co/Rv3gdHH/data.jpg)

#### Accuracy was compbuted using MultiLableFbeta:

![kd](https://i.ibb.co/LC6rJRN/score.jpg)

#### Prediction:

![kd](https://i.ibb.co/k9t2CSC/prediction.jpg)

* Its a copy of my kernel of Bengali Competition on [kaggle](https://i.ibb.co/k9t2CSC/prediction.jpg).
