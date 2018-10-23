

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# Module: tf.contrib.distributions



Defined in [`tensorflow/contrib/distributions/__init__.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/contrib/distributions/__init__.py).

Classes representing statistical distributions and ops for working with them.

See the [Statistical Distributions (contrib)](../../../../api_guides/python/contrib.distributions) guide.

## Modules

[`bijectors`](../../tf/contrib/distributions/bijectors) module: Bijector Ops.

## Classes

[`class Bernoulli`](../../tf/distributions/Bernoulli): Bernoulli distribution.

[`class BernoulliWithSigmoidProbs`](../../tf/contrib/distributions/BernoulliWithSigmoidProbs): Bernoulli with `probs = nn.sigmoid(logits)`.

[`class Beta`](../../tf/distributions/Beta): Beta distribution.

[`class BetaWithSoftplusConcentration`](../../tf/contrib/distributions/BetaWithSoftplusConcentration): Beta with softplus transform of `concentration1` and `concentration0`.

[`class Binomial`](../../tf/contrib/distributions/Binomial): Binomial distribution.

[`class Categorical`](../../tf/distributions/Categorical): Categorical distribution.

[`class Chi2`](../../tf/contrib/distributions/Chi2): Chi2 distribution.

[`class Chi2WithAbsDf`](../../tf/contrib/distributions/Chi2WithAbsDf): Chi2 with parameter transform `df = floor(abs(df))`.

[`class ConditionalDistribution`](../../tf/contrib/distributions/ConditionalDistribution): Distribution that supports intrinsic parameters (local latents).

[`class ConditionalTransformedDistribution`](../../tf/contrib/distributions/ConditionalTransformedDistribution): A TransformedDistribution that allows intrinsic conditioning.

[`class Deterministic`](../../tf/contrib/distributions/Deterministic): Scalar `Deterministic` distribution on the real line.

[`class Dirichlet`](../../tf/distributions/Dirichlet): Dirichlet distribution.

[`class DirichletMultinomial`](../../tf/distributions/DirichletMultinomial): Dirichlet-Multinomial compound distribution.

[`class Distribution`](../../tf/distributions/Distribution): A generic probability distribution base class.

[`class ExpRelaxedOneHotCategorical`](../../tf/contrib/distributions/ExpRelaxedOneHotCategorical): ExpRelaxedOneHotCategorical distribution with temperature and logits.

[`class Exponential`](../../tf/distributions/Exponential): Exponential distribution.

[`class ExponentialWithSoftplusRate`](../../tf/contrib/distributions/ExponentialWithSoftplusRate): Exponential with softplus transform on `rate`.

[`class Gamma`](../../tf/distributions/Gamma): Gamma distribution.

[`class GammaWithSoftplusConcentrationRate`](../../tf/contrib/distributions/GammaWithSoftplusConcentrationRate): `Gamma` with softplus of `concentration` and `rate`.

[`class Geometric`](../../tf/contrib/distributions/Geometric): Geometric distribution.

[`class Independent`](../../tf/contrib/distributions/Independent): Independent distribution from batch of distributions.

[`class InverseGamma`](../../tf/contrib/distributions/InverseGamma): InverseGamma distribution.

[`class InverseGammaWithSoftplusConcentrationRate`](../../tf/contrib/distributions/InverseGammaWithSoftplusConcentrationRate): `InverseGamma` with softplus of `concentration` and `rate`.

[`class Laplace`](../../tf/distributions/Laplace): The Laplace distribution with location `loc` and `scale` parameters.

[`class LaplaceWithSoftplusScale`](../../tf/contrib/distributions/LaplaceWithSoftplusScale): Laplace with softplus applied to `scale`.

[`class Logistic`](../../tf/contrib/distributions/Logistic): The Logistic distribution with location `loc` and `scale` parameters.

[`class Mixture`](../../tf/contrib/distributions/Mixture): Mixture distribution.

[`class MixtureSameFamily`](../../tf/contrib/distributions/MixtureSameFamily): Mixture (same-family) distribution.

[`class Multinomial`](../../tf/distributions/Multinomial): Multinomial distribution.

[`class MultivariateNormalDiag`](../../tf/contrib/distributions/MultivariateNormalDiag): The multivariate normal distribution on `R^k`.

[`class MultivariateNormalDiagPlusLowRank`](../../tf/contrib/distributions/MultivariateNormalDiagPlusLowRank): The multivariate normal distribution on `R^k`.

[`class MultivariateNormalDiagWithSoftplusScale`](../../tf/contrib/distributions/MultivariateNormalDiagWithSoftplusScale): MultivariateNormalDiag with `diag_stddev = softplus(diag_stddev)`.

[`class MultivariateNormalFullCovariance`](../../tf/contrib/distributions/MultivariateNormalFullCovariance): The multivariate normal distribution on `R^k`.

[`class MultivariateNormalTriL`](../../tf/contrib/distributions/MultivariateNormalTriL): The multivariate normal distribution on `R^k`.

[`class NegativeBinomial`](../../tf/contrib/distributions/NegativeBinomial): NegativeBinomial distribution.

[`class Normal`](../../tf/distributions/Normal): The Normal distribution with location `loc` and `scale` parameters.

[`class NormalWithSoftplusScale`](../../tf/contrib/distributions/NormalWithSoftplusScale): Normal with softplus applied to `scale`.

[`class OneHotCategorical`](../../tf/contrib/distributions/OneHotCategorical): OneHotCategorical distribution.

[`class Poisson`](../../tf/contrib/distributions/Poisson): Poisson distribution.

[`class PoissonLogNormalQuadratureCompound`](../../tf/contrib/distributions/PoissonLogNormalQuadratureCompound): `PoissonLogNormalQuadratureCompound` distribution.

[`class QuantizedDistribution`](../../tf/contrib/distributions/QuantizedDistribution): Distribution representing the quantization `Y = ceiling(X)`.

[`class RegisterKL`](../../tf/distributions/RegisterKL): Decorator to register a KL divergence implementation function.

[`class RelaxedBernoulli`](../../tf/contrib/distributions/RelaxedBernoulli): RelaxedBernoulli distribution with temperature and logits parameters.

[`class RelaxedOneHotCategorical`](../../tf/contrib/distributions/RelaxedOneHotCategorical): RelaxedOneHotCategorical distribution with temperature and logits.

[`class ReparameterizationType`](../../tf/distributions/ReparameterizationType): Instances of this class represent how sampling is reparameterized.

[`class SinhArcsinh`](../../tf/contrib/distributions/SinhArcsinh): The SinhArcsinh transformation of a distribution on `(-inf, inf)`.

[`class StudentT`](../../tf/distributions/StudentT): Student's t-distribution.

[`class StudentTWithAbsDfSoftplusScale`](../../tf/contrib/distributions/StudentTWithAbsDfSoftplusScale): StudentT with `df = floor(abs(df))` and `scale = softplus(scale)`.

[`class TransformedDistribution`](../../tf/contrib/distributions/TransformedDistribution): A Transformed Distribution.

[`class Uniform`](../../tf/distributions/Uniform): Uniform distribution with `low` and `high` parameters.

[`class VectorDeterministic`](../../tf/contrib/distributions/VectorDeterministic): Vector `Deterministic` distribution on `R^k`.

[`class VectorDiffeomixture`](../../tf/contrib/distributions/VectorDiffeomixture): VectorDiffeomixture distribution.

[`class VectorExponentialDiag`](../../tf/contrib/distributions/VectorExponentialDiag): The vectorization of the Exponential distribution on `R^k`.

[`class VectorLaplaceDiag`](../../tf/contrib/distributions/VectorLaplaceDiag): The vectorization of the Laplace distribution on `R^k`.

[`class VectorSinhArcsinhDiag`](../../tf/contrib/distributions/VectorSinhArcsinhDiag): The (diagonal) SinhArcsinh transformation of a distribution on `R^k`.

[`class WishartCholesky`](../../tf/contrib/distributions/WishartCholesky): The matrix Wishart distribution on positive definite matrices.

[`class WishartFull`](../../tf/contrib/distributions/WishartFull): The matrix Wishart distribution on positive definite matrices.

## Functions

[`assign_log_moving_mean_exp(...)`](../../tf/contrib/distributions/assign_log_moving_mean_exp): Compute the log of the exponentially weighted moving mean of the exp.

[`assign_moving_mean_variance(...)`](../../tf/contrib/distributions/assign_moving_mean_variance): Compute exponentially weighted moving {mean,variance} of a streaming value.

[`estimator_head_distribution_regression(...)`](../../tf/contrib/distributions/estimator_head_distribution_regression): Creates a `Head` for regression under a generic distribution.

[`kl_divergence(...)`](../../tf/distributions/kl_divergence): Get the KL-divergence KL(distribution_a || distribution_b).

[`matrix_diag_transform(...)`](../../tf/contrib/distributions/matrix_diag_transform): Transform diagonal of [batch-]matrix, leave rest of matrix unchanged.

[`moving_mean_variance(...)`](../../tf/contrib/distributions/moving_mean_variance): Compute exponentially weighted moving {mean,variance} of a streaming value.

[`normal_conjugates_known_scale_posterior(...)`](../../tf/contrib/distributions/normal_conjugates_known_scale_posterior): Posterior Normal distribution with conjugate prior on the mean.

[`normal_conjugates_known_scale_predictive(...)`](../../tf/contrib/distributions/normal_conjugates_known_scale_predictive): Posterior predictive Normal distribution w. conjugate prior on the mean.

[`percentile(...)`](../../tf/contrib/distributions/percentile): Compute the `q`-th percentile of `x`.

[`softplus_inverse(...)`](../../tf/contrib/distributions/softplus_inverse): Computes the inverse softplus, i.e., x = softplus_inverse(softplus(x)).

## Other Members

`FULLY_REPARAMETERIZED`

`NOT_REPARAMETERIZED`

