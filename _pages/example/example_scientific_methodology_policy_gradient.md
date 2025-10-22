### Scientific Methodology of Policy Gradient Methods (Sutton et al.)

* **Observation:** Approximating a value function is theoretically intractable when combined with function approximation.
* **Question/Problem:** How can we create a provably convergent RL algorithm that uses function approximation?
* **Hypothesis:** An explicit, gradient-based policy approximator, aided by an advantage function, will be provably convergent.
* **Method (to test the Hyp.):** Derive a new policy gradient form, suitable for estimation using an approximate advantage function.
* **Experiment:** Conduct a mathematical proof to test the convergence of a policy iteration algorithm using this new gradient formulation.
* **Analysis:** The proof holds, confirming that the algorithm is convergent.
* **Conclusion:** We proved for the first time that this policy iteration method converges to a locally optimal policy.