# Flask Application for Deploying a Machine Learning Model

This repository contains a simplified version of a Flask application for deploying a machine learning model. The example uses the Iris dataset from scikit-learn to predict the species of Iris based on four features: sepal length, sepal width, petal length, and petal width.

## Dependencies

The following dependencies are required to run the Flask application:

- Flask
- scikit-learn
- joblib

You can install the dependencies using pip:

pip install flask scikit-learn joblib
## GitHub Repository

The code for this example can be found in the following GitHub repository: [Link to GitHub Repository](https://github.com/kamalakarpeta/deploy_ML_model_with_flask)

## Conclusion

This Flask application demonstrates a simplified approach to deploying a machine learning model. It creates a web server that listens for POST requests at the `/predict` endpoint. The server expects JSON data with a `features` key containing a list of four numbers representing the sepal length, sepal width, petal length, and petal width. It returns a JSON response with a `prediction` key containing the predicted species of Iris.

To run the Flask application, save the code in a `.py` file and run it using Python from the command line. Make sure to resolve any dependencies and follow the instructions provided in the repository.

It is important to note that this is a simplified example and does not include error checking, logging, or other features that would be necessary in a real-world scenario. Additionally, running the Flask application in an interactive Python environment such as Jupyter Notebook or an IPython shell may result in errors. To avoid this, it is recommended to run the Flask application in a regular Python environment.

Feel free to explore the code in the provided GitHub repository and adapt it to your own projects. You can further enhance the application by adding error handling, logging, and other functionalities as per your requirements.
