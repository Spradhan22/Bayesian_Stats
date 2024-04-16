# Bayesian Analysis

This Python code calculates the posterior distribution of a Beta-Binomial model and plots it using Tkinter for user interaction and Matplotlib for visualization.

## How to Run the Code:

### Prerequisites:

- `Python 3` should be installed on your system.
- Required Python packages: `tkinter`, `numpy`, `matplotlib`, `scipy`.

### Installing required packages:
- Depending on your operating system, open a terminal (Linux/Mac) or command prompt (Windows).
- Run the following commands:

### Running the Code:

1. Save the provided Python code in a file, e.g., `posterior_distribution.py`.
2. Open your terminal.
3. Navigate to the directory where `posterior_distribution.py` is saved.
4. Run the code using the command: `python3 posterior_distribution.py`.
5. The program will open a Tkinter window.
6. Enter the alpha and beta prior values.
7. Click on "Plot Posterior" to visualize the posterior distribution.
8. The plot will display the prior and posterior distributions, along with Maximum Likelihood Estimate (MLE) and Maximum A Posteriori (MAP) estimates.

## Understanding the Code:

1. **plot_posterior():**
 - Calculates the posterior distribution based on user-provided alpha and beta prior values.
 - Plots the prior and posterior distributions using Matplotlib.
 - Calculates and plots the Maximum Likelihood Estimate (MLE) and Maximum A Posteriori (MAP) estimates.

2. **observed_data:**
 - Represents the observed data used for inference.

3. **Tkinter GUI:**
 - Creates a Tkinter window with entry fields for alpha and beta prior values.
 - Provides a button to trigger the plotting of the posterior distribution.

## Code Execution:

- Upon running the script, a Tkinter window opens.
- Users can input alpha and beta prior values.
- Clicking on "Plot Posterior" generates the posterior distribution plot.

## Output:

- The program outputs a graphical representation of the prior and posterior distributions.
- It also displays MLE and MAP estimates on the plot.

## Interpreting the Results:

- Users can observe how the prior distribution is updated to the posterior distribution based on observed data.
- MLE and MAP estimates provide point estimates based on the data and prior information.

## Note:

- Ensure that the observed data and parameter inputs are appropriate for your specific use case.
- Users can modify the observed data and prior parameters according to their needs.
- For any issues or further inquiries, please refer to the code comments or contact the developer team.
