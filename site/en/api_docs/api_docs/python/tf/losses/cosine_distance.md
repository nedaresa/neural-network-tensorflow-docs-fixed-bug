

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.losses.cosine_distance

``` python
cosine_distance(
    labels,
    predictions,
    dim=None,
    weights=1.0,
    scope=None,
    loss_collection=tf.GraphKeys.LOSSES,
    reduction=Reduction.SUM_BY_NONZERO_WEIGHTS
)
```



Defined in [`tensorflow/python/ops/losses/losses_impl.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/ops/losses/losses_impl.py).

Adds a cosine-distance loss to the training procedure.

Note that the function assumes that `predictions` and `labels` are already
unit-normalized.

#### Args:

* <b>`labels`</b>: `Tensor` whose shape matches 'predictions'
* <b>`predictions`</b>: An arbitrary matrix.
* <b>`dim`</b>: The dimension along which the cosine distance is computed.
* <b>`weights`</b>: Optional `Tensor` whose rank is either 0, or the same rank as
    `labels`, and must be broadcastable to `labels` (i.e., all dimensions must
    be either `1`, or the same as the corresponding `losses` dimension).
* <b>`scope`</b>: The scope for the operations performed in computing the loss.
* <b>`loss_collection`</b>: collection to which this loss will be added.
* <b>`reduction`</b>: Type of reduction to apply to loss.


#### Returns:

Weighted loss float `Tensor`. If `reduction` is `NONE`, this has the same
shape as `labels`; otherwise, it is scalar.


#### Raises:

* <b>`ValueError`</b>: If `predictions` shape doesn't match `labels` shape, or
    `dim`, `labels`, `predictions` or `weights` is `None`.