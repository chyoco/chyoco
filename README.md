# chyoco

Independent researcher interested in machine learning theory, safe reinforcement
learning, survival analysis, optimizer dynamics, and certificate-based methods.

Contact: moyashiusdt@gmail.com

This profile is used for research identity verification and contact purposes.

## Current research interests

- finite-family survival preorder recovery
- certificate-driven complexity measures
- safe decision-making under survival constraints
- optimizer-induced loss-spike prediction
- AdamW/SGD training dynamics
- machine learning theory and empirical diagnostics

## Current manuscripts / research projects

### 1. Survival Preorders in Catastrophic MDPs

**Working title:**  
*Survival Preorders in Catastrophic MDPs: Quantile Geometry, Positive
Quantile-Linear Menus, and Minimax Recovery*

This project studies policies through their first-catastrophe survival curves
rather than through a single scalar reward or risk score. The main object is the
finite-family survival-FSD preorder induced by first-catastrophe laws.

Core themes:

- finite-poset realization by catastrophic MDP survival curves
- survival-quantile geometry and witness intervals
- exact point-grid recovery as a hitting-set problem
- positive q-linear menus as conic covers
- minimax sample complexity for exact preorder recovery
- certificate-based verification for finite MDP case studies

### 2. CAPH: Causal Adam-Preconditioned Hazard Predictor

**Working title:**  
*CAPH: Causal Adam-Preconditioned Hazard Predictor for Optimizer-Induced Loss
Spikes*

This project studies whether optimizer-induced probe-loss spikes can be predicted
from causal training-time information available before the spike. The goal is to
estimate the probability of a future spike over a finite horizon using only
current and past optimizer, gradient, update, parameter, schedule, and probe-loss
state.

Core themes:

- AdamW second-moment mismatch
- candidate-update probe-loss lift
- descent-alignment failure
- line-search overshoot risk
- preconditioned noise-to-drift ratio
- layer concentration and tail-update risk
- schedule-leakage residualization
- event-level rare-spike detection

The project focuses on mechanistic, causal predictors of optimizer-induced
training instability. It does not claim universal prediction of all loss spikes;
data shifts or externally induced spikes require separate diagnostics.

## Research direction

My broader research goal is to understand finite, verifiable structure in
machine learning systems: when scalar summaries fail, what richer object should
replace them, and what certificates make the resulting claims checkable?
