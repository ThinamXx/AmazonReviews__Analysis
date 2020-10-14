# **Amazon Reviews Analysis**

**TensorFlow and TensorBoard**
- TensorFlow is a free and open-source software library for Dataflow and differentiable programming across a range of tasks. It is a symbolic Math Library, and is also used for Machine Learning applications such as Neural Networks. TensorFlow's Visualization Toolkit TensorBoard provides the visualization and tooling needed for Machine Learning Experimentation.

**Libraries and Dependencies**
- I have listed all the necessary Libraries and Dependencies required for the Project here:

```javascript
from __future__ import absolute_import, division
from __future__ import print_function, unicode_literals
from IPython.display import display

try:
  !pip uninstall tb-nightly tensorboardX tenosrboard
  !pip install tf-nightly
except Exception:
  pass 

import tensorflow as tf
import os
import datetime
import tensorflow_datasets as tfds

from keras.models import Sequential                                              
from keras.layers import Dense, Bidirectional, LSTM, Dropout, Embedding          
from keras.layers import Flatten

%load_ext tensorboard
```

**Getting the Data**
- I have used Google Colab for this Project so the process of downloading and reading the Data might be different in other platforms. I will use **Amazon Reviews Mobile Electronics Dataset** for this Project and I will import the Dataset using Tensorflow. The Dataset is already present in Tensorflow Dataset Library Corpus.

**Processing the Dataset**
- I have presented the overall Implementation of TensorFlow and TensorBoard in Processing the Data such as Tokenization and Encoding.

![Image](https://github.com/ThinamXx/66Days__NaturalLanguageProcessing/blob/master/Images/Day%2039a.PNG)

**Long Short Term Memory(LSTM)**
- Long Short Term Memory or LSTM is an Artificial Recurrent Neural Network or RNN architecture used in the field of Deep Learning. LSTM has Feedback connections. It can not only process single data points, but also entire sequences of data such as Speech or Video. I have presented the overall Implementation of TensorFlow and TensorBoard in preparing Long Short Term Memory or LSTM Model.

![Image](https://github.com/ThinamXx/66Days__NaturalLanguageProcessing/blob/master/Images/Day%2039b.PNG)

**Model Evaluation**
- I have presented some basic workflow of Model Evaluation and deploying the Trained Model on unseen Text Data for Analysis. I have also presented the simple technique of Data Visualization for evaluating the Model here in the Snapshot.

![Image](https://github.com/ThinamXx/66Days__NaturalLanguageProcessing/blob/master/Images/Day%2040a.PNG)
