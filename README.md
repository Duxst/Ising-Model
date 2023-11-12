# Ising-Model
Explore the behavior of the two-dimensional Ising model in Python using Monte Carlo techniques. This repository compares and analyses the performance of two algorithms: Metropolis-Hastings and Wolff Cluster. 

Monte Carlo Exploration of 2D Ising Model in Python

This repository delves into the behavior of the two-dimensional Ising model using Monte Carlo techniques in Python. It specifically focuses on the comparison and analysis of two algorithms: Metropolis-Hastings and Wolff Cluster.

Key Features:

Algorithmic Performance: Compare and analyze the performance of Metropolis-Hastings and Wolff Cluster algorithms.

Plots for System Properties: Generate insightful plots for magnetic susceptibility and specific heat. These plots are obtained by examining the temperature-dependent magnetization and energy of the system, revealing points of divergence at the critical temperature.

Autocorrelation Study: Investigate autocorrelation to highlight the drawbacks associated with a single flip procedure as opposed to the more efficient cluster flip method.

Dynamic Exponents: Determine the dynamic exponents of both algorithms, providing valuable insights into their behavior. Notably, $z_{Metropolis}$ is found to be 0.9327 ± 0.4025, and $z_{Wolff}$ is 0.1098 ± 0.0772 for the Metropolis and Wolff algorithms, respectively.

Critical Slowing Down: Identify and quantify the issue of critical slowing down, with the Metropolis algorithm showing deviation from the expected value. This underscores the improvements made by the Wolff Cluster algorithm in addressing this challenge.

Usage:

Clone the repository.
Run the Python scripts to explore the Ising model using Monte Carlo techniques.
Analyze the generated plots to gain insights into the system behavior.
Check the dynamic exponents and critical slowing down aspects for algorithmic comparison.
Feel free to contribute, report issues, or suggest improvements. Happy coding and exploring the fascinating world of the 2D Ising model!





