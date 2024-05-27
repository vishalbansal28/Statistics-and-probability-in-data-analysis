## Statistical Distributions and Data Analysis Projects

This repository contains Python code examples demonstrating the use of common statistical distributions: the binomial, geometric, and Poisson distributions. These snippets were developed during a course in Statistics and Probability.

### Projects

1. **Binomial Distribution: Modeling Coin Tosses**

   - **File:** `binomial_distribution.py`
   - **Description:**  This code simulates the binomial distribution, which models the probability of getting a certain number of successes in a fixed number of independent trials. The example focuses on the scenario of flipping a fair coin 20 times and calculating the probabilities of obtaining different numbers of heads.
   - **Key Concepts:** Binomial distribution, probability mass function (PMF), visualization of distributions.

2. **Geometric Distribution: Waiting for Success**

   - **File:** `geometric_distribution.py`
   - **Description:** This code explores the geometric distribution, which models the probability of getting the first success on a specific attempt in a series of independent trials. The example calculates and plots the probabilities of getting the first head on the first, second, or third flip of a coin.
   - **Key Concepts:** Geometric distribution, probability mass function (PMF), waiting time, visualization of distributions.

3. **Poisson Distribution: Modeling Job Arrivals**

   - **File:** `poisson_distribution.py`
   - **Description:** This code demonstrates the Poisson distribution, which models the probability of a certain number of events happening in a fixed interval of time or space, given a constant average rate. The example explores the probability of job arrivals in a computer system with an average rate of 2 jobs per minute.
   - **Key Concepts:** Poisson distribution, probability mass function (PMF), average rate, visualization of distributions.

### How to Run

1. **Install Required Libraries:**
   ```bash
   pip install numpy matplotlib scipy
   ```

2. **Run Each Script:**
   ```bash
   python binomial_distribution.py
   python geometric_distribution.py
   python poisson_distribution.py
   ```

### Further Exploration

- **Vary Parameters:** Experiment with different values for the parameters (e.g., probability of success, number of trials, average rate) to see how the distributions change.
- **Visualization:** Create more elaborate plots to visualize the distributions, such as histograms or line graphs.
- **Real-World Applications:** Research how these distributions are used in various fields, such as finance, healthcare, engineering, or marketing. 
