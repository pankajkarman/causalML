# Syllabus and Schedule

This schedule is subject to adjustment.  Please check frequently to stay updated.

| Date            | Topic                                          | Reading | Out     | Due     |
|-----------------|------------------------------------------------|---------|---------|---------|
|                 |                                                |         |         |         |
| May 8, 2019     | Course Overview                                |         | HW1 Out |         |
| May 15, 2019    | Some useful tools                              |         | HW2 Out | HW1 Due |
| May 22, 2019    | Causal models as generative ML                 |         |         | HW2 Due |
| May 29, 2019    | How to think in DAGs                           |         |         |         |
| June 5, 2019    | Confounding and deconfounding                  |         |         |         |
| June 12, 2019   | Guest Speaker, interventions                   |         |         |         |
| June 19, 2019   | Counterfactuals and overview of class projects |         |         |         |
| June 26, 2019   | Counterfactuals and structural causal models   |         |         |         |
| July 3, 2019    | Causal Deep Generative Models                  |         |         |         |
| July 10, 201    | Causal models and online learning              |         |         |         |
| July 17, 2019   | Counterfactual evaluation for offline learning |         |         |         |
| July 24, 2019   | Causal reinforcement learning                  |         |         |         |
| July 31, 2019   | Converting probabilistic models to SCMs        |         |         |         |
| August 7, 2019  | Project presentations                          |         |         |         |
| August 14, 2019 | Project presentations                          |         |         |         |



## Course Overview (May 8, 2019)
* Syllabus overview and goals of the course
* Background assessment
* Overview of key ideas in statistics, experimentation and science
* Generative modeling and tutorial prep.

## Some useful tools (May 15, 2019)
* Tutorial to R package [bnlearn](http://www.bnlearn.com/)
* Tutorial on the [Pyro](http://pyro.ai/) package in Python
* Survey of other tools, e.g. Python's [pgmpy](https://github.com/pgmpy/pgmpy) and Microsoft's [DoWhy](https://github.com/Microsoft/dowhy)

## Causal models as generative ML (May 22, 2019)
* Ladder of causality 
* Bayesian networks and causal Bayesian networks
* Causal modeling with probabilistic machine learning
* Some useful notation

## How to think in DAGs (May 29, 2019)
* Graph terminology
* V-structures/colliders
* Pearl's d-separation
* Markov property and Markov blanket
* PDAGs and Markov equivalence
* Faithfulness and causal minimality

## Confounding and deconfounding (June 5, 2019)
* Understanding "confounding" with DAGs
* Estimation of treatment effects
* Examples of confounding in machine learning
* Valid adjustment sets, deconfounding techniques, instrumental variables
* Simpson's Paradox, Monte hall, Berkson's Paradox

## Guest Speaker, interventions (June 12, 2019)
* Guest Speaker: [Jeffrey Wong](https://www.linkedin.com/in/jeffctwong/) Senior Modeling Architect, Computational Causal Inference at Netflix
* Interventions and implications to prediction
* Graph mutilation and Pearl's do-calculus
* _do_-calculus as probabilistic metaprogramming
* Propensity matching, G-formula, mediation

## Counterfactuals and overview of class projects (June 19, 2019)
* Counterfactuals and folk metaphysics
* Deep causal generative models with VAEs and GANs
* Inference in deep causal generative models
* Propensity scores in anomaly prediction
* Counterfactual solutions to algorithmic bias
* Counterfactual policy evaluation

## Counterfactuals and structural causal models (June 26, 2019)
* Introduction to structural causal models
* Structural causal models as generative ML
* Computing counterfactuals with structural causal models
* Coding examples

## Causal Deep Generative Models (July 3, 2019)
* Counterfactual inference in variational autoencoders
* Causal implicit generative models
* Counterfactual inference in GANs

## Causal models and online learning (July 10, 2019)
* Online learning with interventions
* Counterfactual Model for Online Systems
* Causal Reasoning for Online Systems

## Counterfactual evaluation for offline learning (July 17, 2019)
* System evaluation via counterfactual estimation
* Inverse probability weighting

## Causal reinforcement learning (July 24, 2019)
* Reinforcement learning from a causal perspective
* Policy evaluation in reinforcement learning

## Converting probabilistic models to SCMs (July 31, 2019)
* Deterministic simulation of random variables
* The identifiability issue
* Causal necessity, sufficiency, and monotonicity
* Using the kernel-trick and Gumbell-max trick

## Project presentations (August 7, 2019)

## Project presentations (August 14, 2019)

# Negative examples

It is useful to learners to understand what was left out and why.  The following topics are included here because they are important topics and are worthy of further study. The reason why they were left out was because of time constraints, or that they are going a bit too deeply down a given area of causal inference with respect to the goals and philosophy of this course.  If students have a special interest in any of these topics and wish to make this the focus of their class project, please discuss it with the instructor or TAs.

### Topics 
* causal discovery
* causal inference with regression models and various canonical SCM models
* doubly-robust estimation
* interference due to network effects (important in social network tech companies like Facebook or Twitter)
* heterogeneous treatment effects
* deep architectures for causal effect inference
* causal time series models
