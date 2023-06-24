# Predict Insurance Bill Deployment (Google)

This project provides a deployment setup for predicting insurance bills using machine learning. It includes a Flask web application and a trained machine learning model.

## Project Structure

The project contains the following files and directories:

- `app.py`: The Flask web application that serves the prediction endpoint.
- `config.py`: Configuration file for the application.
- `deployment_28042020.pkl`: The trained machine learning model used for prediction.
- `Dockerfile`: Dockerfile for containerizing the application.
- `Insurance - Model Training Notebook.ipynb`: Jupyter Notebook containing the model training code.
- `LICENSE`: The license file for the project.
- `README.md`: This readme file.
- `requirements.txt`: List of Python dependencies required by the project.
- `templates/`: Directory containing HTML templates for the web application.
- `.gitignore`: Specifies which files and directories to ignore when committing to Git.
- `.gcloudignore`: Specifies which files and directories to ignore when deploying to Google Cloud Platform.

## Getting Started

To run the project locally, follow these steps:

1. Install the required dependencies by running: `pip install -r requirements.txt`.
2. Run the Flask web application using: `python app.py`.
3. Access the application in your web browser at: `http://localhost:5000`.

## Docker Support

This project includes a Dockerfile for containerization. To build a Docker image, use the following command in the project directory:

```
docker build -t predict-insurance-bill .
```

To run the Docker container, use the following command:

```
docker run -p 5000:5000 predict-insurance-bill
```

## License

This project is licensed under the [MIT License](LICENSE).


