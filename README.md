# POM

**POM** is a unified acquisition strategy for **multi-objective Bayesian optimization (MOBO)**.

The method is motivated by one core question:

**Is the traditional exploration-exploitation concept necessary for global Pareto front discovery?**

If the goal is to discover the global Pareto front, then the quick answer is no. If a method can only perform local exploitation and then requires an additional exploration strategy to correct this behavior, then the exploitation method itself is not suitable for global optimum searching. Instead of designing an extra exploration mechanism to fix this issue afterward, POM is designed from the beginning to directly target global Pareto front discovery.

