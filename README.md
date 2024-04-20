# fastai-api-notes

This is an attempt to condense the FastAI package info. Think of it as a cheatsheet or notes for experienced FastAI developers to directly refer to the code needed for their problem

## Current Set of Imports

```
from fastai.vision.all import *
from fastai.text.all import *
from fastai.collab import *
from fastai.tabular.all import *
```

As mentioned in the docs, fastai’s applications all use the same basic steps and code:
* Create appropriate `DataLoaders`
* Create a `Learner`
* Call a `fit` method
* Make predictions or view results.


