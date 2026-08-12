<h1>Linear Regression From Scratch</h1>

    <p>
        A simple implementation of <strong>Linear Regression from scratch using NumPy</strong>,
        without relying on Scikit-learn's LinearRegression model.
    </p>

    <hr>

    <h2>Overview</h2>

    <p>
        This project demonstrates how Linear Regression works internally by implementing
        the model using mathematical operations and NumPy.
    </p>

    <h3>Features</h3>

    <ul>
        <li>Linear Regression using <strong>Gradient Descent</strong></li>
        <li>Linear Regression using the <strong>Ordinary Least Squares (Normal Equation)</strong></li>
        <li>Model training and prediction</li>
        <li>Weight and bias calculation</li>
        <li>NumPy-based matrix operations</li>
    </ul>

    <hr>

    <h2>Linear Regression</h2>

    <p>
        Linear Regression learns a relationship between input features and a continuous
        target variable.
    </p>

    <p>For a single feature, the model can be represented as:</p>

    <p>
        <strong>y = wx + b</strong>
    </p>

    <ul>
        <li><strong>w</strong> = weight / slope</li>
        <li><strong>b</strong> = bias / intercept</li>
        <li><strong>x</strong> = input feature</li>
        <li><strong>y</strong> = predicted output</li>
    </ul>

    <hr>

    <h2>Methods Implemented</h2>

    <h3>1. Gradient Descent</h3>

    <p>
        Gradient Descent iteratively updates the model's weights and bias to minimize
        the prediction error.
    </p>

    <p>
        <strong>parameter = parameter - learning_rate × gradient</strong>
    </p>

    <h3>2. Ordinary Least Squares</h3>

    <p>
        The Normal Equation provides a direct mathematical solution for the optimal
        parameters:
    </p>

    <p>
        <strong>θ = (X<sup>T</sup>X)<sup>-1</sup>X<sup>T</sup>y</strong>
    </p>

    <p>
        This approach calculates the parameters without iterative optimization.
    </p>

    <hr>

    <h2>Technologies Used</h2>

    <ul>
        <li>Python</li>
        <li>NumPy</li>
        <li>Jupyter Notebook</li>
        <li>Matplotlib</li>
    </ul>

    <hr>

    <h2>Project Structure</h2>

    <pre>
Linear-Regression/
│
├── linear_reg_scratch.ipynb
└── README.md
    </pre>

    <hr>

    <h2>How to Run</h2>

    <ol>
        <li>
            Clone the repository:
            <pre>git clone &lt;your-repository-url&gt;</pre>
        </li>

        <li>
            Open the project folder:
            <pre>cd Linear-Regression</pre>
        </li>

        <li>
            Install the required libraries:
            <pre>pip install numpy matplotlib jupyter</pre>
        </li>

        <li>
            Open the notebook:
            <pre>jupyter notebook linear_reg_scratch.ipynb</pre>
        </li>
    </ol>

    <hr>

    <h2>Learning Objectives</h2>

    <p>
        This project was created to understand the fundamentals of Linear Regression
        rather than simply using a pre-built machine learning algorithm.
    </p>

    <p>It helps demonstrate:</p>

    <ul>
        <li>How weights and bias are learned</li>
        <li>How Gradient Descent works</li>
        <li>How predictions are generated</li>
        <li>How the Normal Equation solves Linear Regression</li>
        <li>How NumPy can be used to implement ML algorithms from scratch</li>
    </ul>

    <hr>

    <h2>Future Improvements</h2>

    <ul>
        <li>Add Mean Squared Error (MSE)</li>
        <li>Add R² score</li>
        <li>Add loss visualization</li>
        <li>Support multiple features</li>
        <li>Add train/test split</li>
    </ul>

    <hr>

    <h2>Author</h2>

    <p>
        <strong>Priyanshu</strong>
    </p>

    <p>
        Built as part of my Machine Learning learning journey.
    </p>
