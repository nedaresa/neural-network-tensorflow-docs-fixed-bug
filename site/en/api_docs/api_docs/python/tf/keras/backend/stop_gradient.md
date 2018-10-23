

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.keras.backend.stop_gradient

``` python
stop_gradient(variables)
```



Defined in [`tensorflow/python/keras/_impl/keras/backend.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/keras/_impl/keras/backend.py).

Returns `variables` but with zero gradient w.r.t. every other variable.

#### Arguments:

* <b>`variables`</b>: Tensor or list of tensors to consider constant with respect
      to any other variable.



#### Returns:

A single tensor or a list of tensors (depending on the passed argument)
that has no gradient with respect to any other variable.