# ACTIVITY RECOGNISITION SYSTEM
This model tells whether a person is jogging, running, going upstairs or downstairs.

![68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f323030302f312a766a4d79467665665251624c697837574179514131772e706e67](https://user-images.githubusercontent.com/72206563/144272052-da4b6a22-5b53-44f3-8e2c-acc75eb67f46.png)

DATASET LINK-http://www.cis.fordham.edu/wisdm/dataset.php

```python
import tensorflow as tf
from tensorflow.keras import Sequential
from tensorflow.keras.layers import Flatten, Dense, Dropout, BatchNormalization
from tensorflow.keras.layers import Conv2D, MaxPool2D
from tensorflow.keras.optimizers import Adam
print(tf.__version__)
```
