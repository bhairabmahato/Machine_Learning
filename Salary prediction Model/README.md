<!DOCTYPE html>
<html>
<head>
</head>
<body>

<h1>Salary Prediction Model for HR Department</h1>

<p>This project involves building a machine learning model to assist the HR department in predicting salaries for future candidates based on their experience, written test scores, and personal interview scores. The model is trained using historical data provided in the "hiring.csv" file, which contains hiring statistics for a firm.</p>

<h2>Dataset Description</h2>

<ul>
  <li>Experience (in years)</li>
  <li>Written Test Score (out of 10)</li>
  <li>Interview Score (out of 10)</li>
  <li>Salary ($) - Target variable</li>
</ul>

<h2>Preprocessing Steps</h2>

<ol>
  <li><strong>Handling Missing Values:</strong></li>
  <ul>
    <li>Filled missing values in the "test_score(out of 10)" column with the median value.</li>
    <li>Filled missing values in the "experience" column with 'zero'.</li>
  </ul>
  <li><strong>Data Encoding:</strong></li>
  <ul>
    <li>Replaced categorical experience values with numerical equivalents.</li>
  </ul>
</ol>

<h2>Machine Learning Model</h2>

<p>Used a linear regression model to predict salaries based on the features: experience, test score, and interview score.</p>

<h2>Predictions</h2>

<p>The model was used to predict salaries for the following candidates:</p>

<ol>
  <li>Candidate 1:</li>
  <ul>
    <li>Experience: 2 years</li>
    <li>Test Score: 9</li>
    <li>Interview Score: 6</li>
    <li>Predicted Salary: $XXXXX</li>
  </ul>
  <li>Candidate 2:</li>
  <ul>
    <li>Experience: 12 years</li>
    <li>Test Score: 10</li>
    <li>Interview Score: 10</li>
    <li>Predicted Salary: $XXXXX</li>
  </ul>
</ol>

<h2>Instructions</h2>

<p>To replicate the results or make predictions for new candidates:</p>
<ol>
  <li>Ensure you have the "hiring.csv" dataset.</li>
  <li>Use the provided Python code to preprocess the data and train the machine learning model.</li>
  <li>Modify the input values in the prediction section to predict salaries for new candidates.</li>
</ol>

<h2>Usage</h2>

<p>Feel free to use and modify this model for your HR department's salary prediction needs. 
  <br> For any questions or issues, contact [Bhairab Mahato / bhairabmahato7384@gmail.com].</p>

</body>
</html>

