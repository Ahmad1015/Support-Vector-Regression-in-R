# Support Vector Regression (SVR) - R Project

This project demonstrates the implementation of Support Vector Regression (SVR) in R. SVR is a powerful machine learning technique used for regression tasks. It's particularly useful when dealing with non-linear relationships between variables.

## Getting Started

Follow these instructions to understand and run the code on your local machine.

### Prerequisites

Before running the code, ensure you have R installed on your system. You'll also need to install the 'e1071' and 'ggplot2' packages, which are used in the project. You can install them using the following commands in your R console:

```R
install.packages('e1071')
install.packages('ggplot2')
```
## Code Overview
The R script contains the following key steps:

- Importing the Dataset: The code reads a dataset named 'Position_Salaries.csv' and selects columns 'Level' and 'Salary' for analysis.
- Fitting SVR to the Dataset: It uses the 'e1071' library to fit an SVR model to the dataset. The SVR model is configured with an epsilon-regression type and a radial kernel.
- Predicting a New Result: The trained SVR model is used to predict the salary for a new data point with 'Level' equal to 6.5.
- Visualizing the SVR Results: The code utilizes 'ggplot2' for data visualization. It creates two plots. The first plot displays the actual data points (red dots) and the SVR predictions (blue line). The second plot provides a smoother curve of SVR predictions over a higher-resolution range of 'Level' values.

## Usage
To run the code:
- Ensure you have R and the required packages installed.
- Place your dataset (in this case, 'Position_Salaries.csv') in the same directory as the R script.
- Open the R script in your preferred R environment.
- Run the script. It will execute the SVR model training, prediction, and visualization.
- Observe the SVR predictions and plots to understand the regression results.

## Contributing
Contributions to this project, such as code improvements or additional features, are welcome. Feel free to submit pull requests.

## License
This project is licensed under the MIT License.
## Credits

This project was inspired by the "Machine Learning A-Z™: AI, Python & R + ChatGPT Bonus [2023]" course on Udemy, created by:

- Kirill Eremenko
- Hadelin de Ponteves
- SuperDataScience Team
- Ligency Team

I acknowledge and thank the instructors and teams behind this course for providing valuable knowledge and resources. You can find the course on Udemy at https://www.udemy.com/course/machinelearning/.

Feel free to explore and modify the code to suit your needs and continue your learning journey in machine learning and data science.
