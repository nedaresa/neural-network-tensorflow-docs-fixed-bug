

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# Module: tf.contrib.opt



Defined in [`tensorflow/contrib/opt/__init__.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/contrib/opt/__init__.py).

A module containing optimization routines.

## Classes

[`class DropStaleGradientOptimizer`](../../tf/contrib/opt/DropStaleGradientOptimizer): Wrapper optimizer that checks and drops stale gradient.

[`class ExternalOptimizerInterface`](../../tf/contrib/opt/ExternalOptimizerInterface): Base class for interfaces with external optimization algorithms.

[`class LazyAdamOptimizer`](../../tf/contrib/opt/LazyAdamOptimizer): Variant of the Adam optimizer that handles sparse updates more efficiently.

[`class MovingAverageOptimizer`](../../tf/contrib/opt/MovingAverageOptimizer): Optimizer that computes a moving average of the variables.

[`class NadamOptimizer`](../../tf/contrib/opt/NadamOptimizer): Optimizer that implements the Nadam algorithm.

[`class ScipyOptimizerInterface`](../../tf/contrib/opt/ScipyOptimizerInterface): Wrapper allowing `scipy.optimize.minimize` to operate a `tf.Session`.

[`class VariableClippingOptimizer`](../../tf/contrib/opt/VariableClippingOptimizer): Wrapper optimizer that clips the norm of specified variables after update.

