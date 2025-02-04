```RuntimeError: Failed to import transformers.models.roberta.modeling_tf_roberta because of the following error (look up to see its traceback):partially initialized module 'tf_keras.src' has no attribute 'utils' (most likely due to a circular import)```

### IF THIS ERROR OCCURS

```pip install --upgrade tensorflow transformers```

```pip uninstall keras tensorflow tensorflow-cpu keras-nightly keras-preprocessing -y```

```pip install tensorflow```

### Write these codes in the previous cell in the python environment
