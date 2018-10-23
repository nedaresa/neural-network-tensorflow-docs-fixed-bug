

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# Module: tf.contrib.kfac.fisher_blocks



Defined in [`tensorflow/contrib/kfac/python/ops/fisher_blocks_lib.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/contrib/kfac/python/ops/fisher_blocks_lib.py).

FisherBlock definitions.

## Classes

[`class ConvDiagonalFB`](../../../tf/contrib/kfac/fisher_blocks/ConvDiagonalFB): FisherBlock for convolutional layers using a diagonal approx.

[`class ConvKFCBasicFB`](../../../tf/contrib/kfac/fisher_blocks/ConvKFCBasicFB): FisherBlock for 2D convolutional layers using the basic KFC approx.

[`class FisherBlock`](../../../tf/contrib/kfac/fisher_blocks/FisherBlock): Abstract base class for objects modeling approximate Fisher matrix blocks.

[`class FullFB`](../../../tf/contrib/kfac/fisher_blocks/FullFB): FisherBlock using a full matrix estimate (no approximations).

[`class FullyConnectedDiagonalFB`](../../../tf/contrib/kfac/fisher_blocks/FullyConnectedDiagonalFB): FisherBlock for fully-connected (dense) layers using a diagonal approx.

[`class FullyConnectedKFACBasicFB`](../../../tf/contrib/kfac/fisher_blocks/FullyConnectedKFACBasicFB): K-FAC FisherBlock for fully-connected (dense) layers.

[`class KroneckerProductFB`](../../../tf/contrib/kfac/fisher_blocks/KroneckerProductFB): A base class for FisherBlocks with separate input and output factors.

[`class NaiveDiagonalFB`](../../../tf/contrib/kfac/fisher_blocks/NaiveDiagonalFB): FisherBlock using a diagonal matrix approximation.

