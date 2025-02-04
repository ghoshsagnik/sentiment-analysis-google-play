```RuntimeError: Failed to import transformers.models.roberta.modeling_tf_roberta because of the following error (look up to see its traceback):partially initialized module 'tf_keras.src' has no attribute 'utils' (most likely due to a circular import)```

### IF THIS ERROR OCCURS

```python pip install --upgrade tensorflow transformers```
```python pip install tensorflow==2.12 transformers==4.31```
