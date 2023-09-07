<!DOCTYPE html>
<html>

<head>
    <title>House Price Estimation</title>
</head>

<body>

    <h1>House Price Estimation</h1>

    <h2>Predicting Property Values in King County, Seattle</h2>

    <p>Welcome to our House Price Estimation project repository. Here, we harness the power of machine learning to
        forecast property sale prices in King County, Seattle. Our aim is to provide valuable insights and precise
        predictions for the dynamic real estate market.</p>

    <h2>Project Inspiration</h2>

    <p>This endeavor is driven by the desire to build a robust model capable of accurately estimating property prices.
        Such a model has practical implications for both buyers and sellers, enabling them to make well-informed
        decisions and gain a deeper understanding of property valuation.</p>

    <h2>Project Overview</h2>

    <p>This project unfolds in the following phases:</p>
    <ul>
        <li><strong>Data Refinement and Preprocessing:</strong> Ensuring data integrity and consistency.</li>
        <li><strong>Exploratory Data Analysis (EDA):</strong> Uncovering hidden patterns and gaining insights.</li>
        <li><strong>Feature Selection:</strong> Identifying the most influential features.</li>
        <li><strong>Model Training and Assessment:</strong> Employing Linear Regression, Decision Tree, Random Forest
            (degree 2 and 3), and fine-tuning model hyperparameters.</li>
        <li><strong>Comparative Model Analysis:</strong> Drawing conclusions based on model performance and the insights
            we derive.</li>
    </ul>

    <h2>Dataset Overview</h2>

    <p>Our dataset comprises property sale records spanning from May 2014 to May 2015, encompassing a diverse set of
        features including bedrooms, bathrooms, square footage, condition, grade, and more.</p>

    <h2>Getting Started</h2>

    <ol>
        <li>Open the <code>House_Price_Estimation.ipynb</code> notebook.</li>
        <li>Follow the step-by-step instructions provided within.</li>
    </ol>

    <h2>Key Features</h2>

    <ul>
        <li>Thorough data analysis and insightful visualizations.</li>
        <li>Multiple machine learning models for precision predictions.</li>
        <li>Rigorous hyperparameter optimization for model excellence.</li>
    </ul>

    <h2>Technologies Utilized</h2>

    <ul>
        <li>Python</li>
        <li>Pandas</li>
        <li>NumPy</li>
        <li>Scikit-learn</li>
        <li>Matplotlib</li>
        <li>Seaborn</li>
        <li>Jupyter Notebook</li>
    </ul>

    <h2>Project Workflow</h2>

    <ol>
        <li>Import Data and Assess Dataset Dimensions</li>
        <li>Handle Missing Data</li>
        <li>Investigate Column Types and Statistic Summaries</li>
        <li>Execute Univariate Analysis</li>
        <li>Perform Bivariate Analysis</li>
        <li>Eliminate Redundant Columns</li>
        <li>Encode Categorical Variables</li>
        <li>Partition Data into Training and Testing Sets</li>
        <li>Standardize Features</li>
        <li>Train and Evaluate Models (Linear Regression, Decision Tree, Random Forest)</li>
        <li>Fine-Tune Model Parameters for Optimization</li>
        <li>Scrutinize and Analyze Model Performance</li>
        <li>Determine the Optimal Model for Property Price Estimation</li>
    </ol>

    <h2>In-Depth Data Exploration (IDE)</h2>

    <p>Immerse yourself in data distributions, correlations, and the visualization of intriguing data patterns.
        Visualizations include histograms, scatter plots, and correlation heatmaps.</p>

    <h2>Model Training and Evaluation</h2>

    <p>Efficiently implement and train machine learning models, optimize hyperparameters, and assess performance using
        R-squared and RMSE metrics.</p>

    <h2>Outcomes</h2>

    <h3>Model Effectiveness</h3>

    <p>After rigorous scrutiny and model assessment:</p>
    <ul>
        <li><strong>Linear Regression:</strong> R2-Score: 0.6807, RMSE: 203796.0159</li>
        <li><strong>Decision Tree:</strong> R2-Score: 0.7043, RMSE: 196142.2947</li>
        <li><strong>Random Forest:</strong> R2-Score: 0.8710, RMSE: 129540.4012</li>
        <li><strong>Polynomial Regression (Degree 2):</strong> R2-Score: 0.7869, MSE: 29888549258.824467</li>
        <li><strong>Polynomial Regression (Degree 3):</strong> R2-Score: -6250056939565539.0, MSE: 8.76672289925631e+26
        </li>
    </ul>

    <h2>Concluding Remarks</h2>

    <p>The Random Forest model emerges as the top-performing model for estimating property prices, achieving a remarkable
        R2-Score of 0.8710 and a minimal RMSE. Our project's extensive analysis and well-executed machine learning
        techniques provide invaluable insights into the real estate market. We invite you to delve into the Jupyter
        notebook for an in-depth exploration of this project.</p>

</body>

</html>
