

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.contrib.learn.infer_real_valued_columns_from_input

``` python
infer_real_valued_columns_from_input(x)
```



Defined in [`tensorflow/contrib/learn/python/learn/estimators/estimator.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/contrib/learn/python/learn/estimators/estimator.py).

See the guide: [Learn (contrib) > Input processing](../../../../../api_guides/python/contrib.learn#Input_processing)

Creates `FeatureColumn` objects for inputs defined by input `x`.

This interprets all inputs as dense, fixed-length float values.

#### Args:

* <b>`x`</b>: Real-valued matrix of shape [n_samples, n_features...]. Can be
     iterator that returns arrays of features.


#### Returns:

List of `FeatureColumn` objects.