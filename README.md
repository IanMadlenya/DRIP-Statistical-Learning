#DRIP Statistical Learning

**v2.34**  *2 October 2016*

DRIP Statistical Learning is a collection of Java libraries for Machine Learning and Statistical Evaluation.

DRIP Statistical Learning is composed of the following main libraries:
 * Probabilistic Sequence Measure Concentration Bounds Library
 * Statistical Learning Theory Framework Library
 * Empirical Risk Minimization Library
 * VC and Capacity Measure Library
 * Covering Numbers Library

For Installation, Documentation and Samples, and the associated supporting Numerical Libraries please check out [DRIP] (https://github.com/lakshmiDRIP/DRIP).


##Features

###Probabilistic Bounds and Concentration of Measure Sequences
####Probabilistic Bounds
 * Tail Probability Bounds Estimation
 * Basic Probability Inequalities
 * Cauchy-Schwartz Inequality
 * Association Inequalities
 * Moment, Gaussian, and Exponential Bounds
 * Bounding Sums of Independent Random Variables
 * Non Moment Based Bounding - Hoeffding Bound
 * Moment Based Bounds
 * Binomial Tails
 * Custom Bounds for Special i.i.d. Sequences

####Efron Stein Bounds
 * Martingale Differences Sum Inequality
 * Efron-Stein Inequality
 * Bounded Differences Inequality
 * Bounded Differences Inequality - Applications
 * Self-Bounding Functions
 * Configuration Functions
 
####Entropy Methods
 * Information Theory - Basics
 * Tensorization of the Entropy
 * Logarithmic Sobolev Inequalities
 * Logarithmic Sobolev Inequalities - Applications
 * Exponential Inequalities for Self-Bounding Functions
 * Combinatorial Entropy
 * Variations on the Theme of Self-Bounding Functions

####Concentration of Measure
 * Equivalent Bounded Differences Inequality
 * Convex Distance Inequality
 * Convex Distance Inequality - Proof
 * Application of the Convex Distance Inequality - Bin Packing

###Statistical Learning Theory - Foundation and Framework
####Standard SLT Framework
 * Computational Learning Theory
 * Probably Approximately Correct (PAC) Learning
 * PAC Definitions and Terminology
 * SLT Setup
 * Algorithms for Reducing Over-fitting
 * Bayesian Normalized Regularizer Setup

####Generalization and Consistency
 * Types of Consistency
 * Bias-Variance or Estimation-Approximation Trade-off
 * Bias-Variance Decomposition
 * Bias-Variance Optimization
 * Generalization and Consistency for kNN

###Empirical Risk Minimization - Principles and Techniques
####Empirical Risk Minimization
 * Overview
 * The Loss Functions and Empirical Risk Minimization Principles
 * Application of the Central Limit Theorem (CLT) and the Law of Large Numbers (LLN)
 * Inconsistency of Empirical Risk Minimizers
 * Uniform Convergence
 * ERM Complexity

####Symmetrization
 * The Symmetrization Lemma

####Generalization Bounds
 * The Union Bound
 * Shattering Coefficient
 * Empirical Risk Generalization Bound
 * Large Margin Bounds

####Rademacher Complexity
 * Rademacher-based Uniform Convergence
 * VC Entropy
 * Chaining Technique

####Local Rademacher Averages
 * Star-Hull and Sub-Root Functions
 * Local Rademacher Averages and Fixed Point
 * Local Rademacher Averages - Consequences

####Normalized ERM
 * Computing the Normalized Empirical Risk Bounds
 * De-normalized Bounds

####Noise Conditions
 * SLT Analysis Metrics
 * Types of Noise Conditions
 * Relative Loss Class

###VC Theory and Capacity Measure Analysis
####VC Theory and VC Dimension
 * Empirical Processes
 * Bounding the Empirical Loss Function
 * VC Dimension - Setup
 * Incorporating the Formal VC Definition
 * VC Dimension Examples
 * VC Dimension vs. Popper's Dimension

####Sauer Lemma and VC Classifier Framework
 * Working out Sauer Lemma Bounds
 * Sauer Lemma ERM Bounds
 * VC Index
 * VC Classifier Framework

###Capacity/Complexity Estimation Using Covering Numbers
####Covering and Entropy Numbers
 * Nomenclature- Normed Spaces
 * Covering, Entropy, and Dyadic Numbers
 * Background and Overview of Basic Results

####Covering Numbers for Real-Valued Function Classes
 * Functions of Bounded Variation
 * Functions of Bounded Variation - Upper Bound
 * Functions of Bounded Variation - Lower Bound
 * General Function Classes
 * General Function Class Bounds
 * General Function Class Bounds - Lemmas
 * General Function Class - Upper Bounds
 * General Function Class - Lower Bounds

####Operator Theory Methods for Entropy Numbers
 * Generalization Bounds via Uniform Convergence
 * Basic Uniform Convergence Bounds
 * Loss Function Induced Classes
 * Standard Form of Uniform Convergence

####Kernel Machines
 * SVM Capacity Control
 * Nonlinear Kernels
 * Generalization Performance of Regularization Networks
 * Covering Number Determination Steps
 * Challenges Presenting Master Generalization Error

####Entropy Number for Kernel Machines
 * Mercer Kernels
 * Equivalent Kernels
 * Mapping Phi into L2
 * Corrigenda to the Mercer Conditions
 * L2 Unit Ball -> Epsilon Mapping Scaling Operator
 * Unit Bounding Operator Entropy Numbers
 * The SVM Operator
 * Maurey's Theorem
 * Bounds for SV Classes
 * Asymptotic Rates of Decay for the Entropy Numbers

####Discrete Spectra of Convolution Operators
 * Kernels with Compact/Non-compact Support
 * The Kernel Operator Eigenvalues
 * Choosing Nu
 * Extensions to d-dimensions

####Covering Numbers for Given Decay Rates
 * Asymptotic/Non-asymptotic Decay of Covering Numbers
 * Polynomial Eigenvalue Decay
 * Summation and Integration of Non-decreasing Functions
 * Exponential Polynomial Decay

####Kernels for High-Dimensional Data
 * Kernel Fourier Transforms
 * Degenerate Kernel Bounds
 * Covering Numbers for Degenerate Systems
 * Bounds for Kernels in R^d
 * Impact of the Fourier Transform Decay on the Entropy Numbers

####Regularization Networks Entropy Numbers Determination - Practice
 * Custom Applications of the Kernel Machines Entropy Numbers
 * Extensions to the Operator-Theoretic Viewpoint for Covering Numbers


##Contact

lakshmi@synergicdesign.com
