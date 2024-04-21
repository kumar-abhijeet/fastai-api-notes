# fastai-api-notes

This is an attempt to condense the FastAI package info. Think of it as a cheatsheet or notes for experienced FastAI developers to directly refer to the code needed for their problem

## Current Set of Imports

```
from fastai.vision.all import *
from fastai.text.all import *

# we will not cover these two. scikit-learn / other standard python packages can be used for such use cases
from fastai.collab import *
from fastai.tabular.all import *
```

As mentioned in the docs, fastai’s applications all use the same basic steps and code:
* Create appropriate `DataLoaders`
* Create a `Learner`
* Call a `fit` method
* Make predictions or view results.


## Know your Deep Learning Problem: Problems covered by FastAI API

Vision:

* Classification
    * Single-label
    * Multi-label
* Image Localization
    * Segmentation (predict the class of each pixel of an image)
    * Coordinate Predictions (predict one or several key points on an image)
    * Object Detection (draw a box around objects to detect)
