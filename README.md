I replicated the results shown on Fig. 1, Fig. 2 and eq. 2 on the paper "Macroscopic description for networks of spiking neurons" by Ernest Montbrió Diego Pazó and Alex Roxin, as part of a final project for a Nonlinear Dynamics course @ Universidad de Buenos Aires.

![The system of equations for the firing rate and mean membrane potential](https://github.com/ttdduu/montbrio_paper_replication/assets/70667629/faf90ab0-d8d5-40fa-ad3f-992632cc6bbe)
*The system of equations for the firing rate and mean membrane potential*


![a: Parameter space (phase diagram), b and c: bifurcation diagrams for J=15 and d: phase portrait of the system](https://github.com/ttdduu/montbrio_paper_replication/assets/70667629/35d1e78e-61cb-43e0-9eeb-dc0e78e2fb30)
*a: Parameter space (phase diagram), b and c: bifurcation diagrams for J=15 and d: phase portrait of the system*

Eq. 12 describes a system of two ordinary differential equations for the firing rate and mean membrane potential of neuronal networks of heterogeneous, all-to-all coupled quadratic integrate-and-fire (QIF) neurons, which are the canonical model of a Hodkin-Huxley neuron of class 1 excitability, in which a resting state disappears through a saddle-node bifurcation.

In this notebook I'll be exploring parameter space of eq. 12 by having studied its fixed points and therefore the parameter values for which this dynamical system is near bifurcation points: spiral-node and saddle-node transitions. The following video allows for an intuition of the regimes the mean membrane potential and firing rate can acquire when forced by a sinusoidal current injection, which in turn yields v(t) and r(t); the mean membrane potential and firing rate.

https://github.com/ttdduu/montbrio_paper_replication/assets/70667629/2a7cc50a-904c-45e9-990e-a74e0e3f3291
