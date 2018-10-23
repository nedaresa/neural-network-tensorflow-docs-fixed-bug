

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# Module: tf.contrib.seq2seq

### Module `tf.contrib.seq2seq`



Defined in [`tensorflow/contrib/seq2seq/__init__.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.2/tensorflow/contrib/seq2seq/__init__.py).

Ops for building neural network seq2seq decoders and losses.

See the [Seq2seq Library (contrib)](../../../../api_guides/python/contrib.seq2seq) guide.

## Classes

[`class AttentionMechanism`](../../tf/contrib/seq2seq/AttentionMechanism)

[`class AttentionWrapper`](../../tf/contrib/seq2seq/AttentionWrapper): Wraps another `RNNCell` with attention.

[`class AttentionWrapperState`](../../tf/contrib/seq2seq/AttentionWrapperState): `namedtuple` storing the state of a `AttentionWrapper`.

[`class BahdanauAttention`](../../tf/contrib/seq2seq/BahdanauAttention): Implements Bhadanau-style (additive) attention.

[`class BasicDecoder`](../../tf/contrib/seq2seq/BasicDecoder): Basic sampling decoder.

[`class BasicDecoderOutput`](../../tf/contrib/seq2seq/BasicDecoderOutput)

[`class BeamSearchDecoder`](../../tf/contrib/seq2seq/BeamSearchDecoder): BeamSearch sampling decoder.

[`class BeamSearchDecoderOutput`](../../tf/contrib/seq2seq/BeamSearchDecoderOutput)

[`class BeamSearchDecoderState`](../../tf/contrib/seq2seq/BeamSearchDecoderState)

[`class CustomHelper`](../../tf/contrib/seq2seq/CustomHelper): Base abstract class that allows the user to customize sampling.

[`class Decoder`](../../tf/contrib/seq2seq/Decoder): An RNN Decoder abstract interface object.

[`class FinalBeamSearchDecoderOutput`](../../tf/contrib/seq2seq/FinalBeamSearchDecoderOutput): Final outputs returned by the beam search after all decoding is finished.

[`class GreedyEmbeddingHelper`](../../tf/contrib/seq2seq/GreedyEmbeddingHelper): A helper for use during inference.

[`class Helper`](../../tf/contrib/seq2seq/Helper): Interface for implementing sampling in seq2seq decoders.

[`class LuongAttention`](../../tf/contrib/seq2seq/LuongAttention): Implements Luong-style (multiplicative) attention scoring.

[`class SampleEmbeddingHelper`](../../tf/contrib/seq2seq/SampleEmbeddingHelper): A helper for use during inference.

[`class ScheduledEmbeddingTrainingHelper`](../../tf/contrib/seq2seq/ScheduledEmbeddingTrainingHelper): A training helper that adds scheduled sampling.

[`class ScheduledOutputTrainingHelper`](../../tf/contrib/seq2seq/ScheduledOutputTrainingHelper): A training helper that adds scheduled sampling directly to outputs.

[`class TrainingHelper`](../../tf/contrib/seq2seq/TrainingHelper): A helper for use during training.  Only reads inputs.

## Functions

[`dynamic_decode(...)`](../../tf/contrib/seq2seq/dynamic_decode): Perform dynamic decoding with `decoder`.

[`gather_tree(...)`](../../tf/contrib/seq2seq/gather_tree): Calculates the full beams from the per-step ids and parent beam ids.

[`hardmax(...)`](../../tf/contrib/seq2seq/hardmax): Returns batched one-hot vectors.

[`sequence_loss(...)`](../../tf/contrib/seq2seq/sequence_loss): Weighted cross-entropy loss for a sequence of logits.

[`tile_batch(...)`](../../tf/contrib/seq2seq/tile_batch): Tile the batch dimension of a (possibly nested structure of) tensor(s) t.
