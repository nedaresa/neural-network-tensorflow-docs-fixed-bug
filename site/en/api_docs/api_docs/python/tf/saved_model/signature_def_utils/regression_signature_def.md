

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.saved_model.signature_def_utils.regression_signature_def

``` python
regression_signature_def(
    examples,
    predictions
)
```



Defined in [`tensorflow/python/saved_model/signature_def_utils_impl.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/saved_model/signature_def_utils_impl.py).

Creates regression signature from given examples and predictions.

#### Args:

* <b>`examples`</b>: `Tensor`.
* <b>`predictions`</b>: `Tensor`.


#### Returns:

A regression-flavored signature_def.


#### Raises:

* <b>`ValueError`</b>: If examples is `None`.