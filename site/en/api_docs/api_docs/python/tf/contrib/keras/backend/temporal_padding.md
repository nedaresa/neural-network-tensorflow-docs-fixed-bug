

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.contrib.keras.backend.temporal_padding

``` python
temporal_padding(
    x,
    padding=(1, 1)
)
```



Defined in [`tensorflow/contrib/keras/python/keras/backend.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.3/tensorflow/contrib/keras/python/keras/backend.py).

Pads the middle dimension of a 3D tensor.

#### Arguments:

    x: Tensor or variable.
    padding: Tuple of 2 integers, how many zeros to
        add at the start and end of dim 1.


#### Returns:

    A padded 3D tensor.