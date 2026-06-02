Clinical Trial Data Analysis – Heart Disease Study

This project is based on analysing a clinical-style dataset to understand factors that may be linked to heart disease. The idea behind the project was to take a real dataset, clean it, explore it properly, and then apply some basic statistical methods to see if there are any meaningful patterns.

The dataset used contains information on over 1000 patients, including age, cholesterol levels, blood pressure, and other clinical attributes. It also includes a target variable indicating whether a patient has heart disease or not.

I started by checking the data quality. There were no missing values, which made things easier, but several columns were in text format, so I converted those into numerical form to make them usable for analysis. This step is important because most statistical methods and models require numeric input.

Once the data was ready, I explored it to get a general understanding. I looked at how heart disease cases were distributed and compared different variables like age and cholesterol between patients with and without heart disease. This helped identify some initial patterns.

One of the main parts of the project was running a statistical test to check whether cholesterol levels were significantly different between the two groups. I used a t-test for this. The results showed that the difference was statistically significant (p-value less than 0.05).

Interestingly, the results were not what I expected. Patients without heart disease actually had slightly higher average cholesterol levels compared to those with heart disease. This was a useful reminder that real-world data does not always follow assumptions, and that a single variable is often not enough to explain a condition like heart disease.

This project helped me understand the importance of data cleaning, careful analysis, and validating assumptions using statistical methods. It also showed how healthcare data needs to be approached with a bit more depth rather than relying on simple conclusions.

Tools used in this project include Python (Pandas for data handling, SciPy for statistical testing) and basic visualisation libraries. The analysis was done in a Jupyter/Colab notebook.

If I were to extend this project further, I would look into building predictive models and analysing multiple variables together to get a more complete picture of what drives heart disease risk.
