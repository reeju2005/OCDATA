# OCDATA Flask Application

This project is a Flask web application that utilizes a machine learning model to make predictions based on user input. 

## Files Overview

- **app.py**: The main application file that handles HTTP requests, processes input data, and renders the results.
- **requirements.txt**: Contains the necessary dependencies for the project, including Flask and NumPy.
- **Procfile**: Specifies the command to run the application for deployment on platforms like Heroku.
- **README.md**: Documentation for the project, including setup and usage instructions.

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   cd OCDATA
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

5. Run the application:
   ```
   python app.py
   ```

6. Open your web browser and go to `http://127.0.0.1:5000` to access the application.

## Usage

- Input the required values in the form provided on the homepage.
- Submit the form to receive predictions based on the input data.

## Deployment

To deploy the application, ensure you have a `Procfile` configured and follow the deployment instructions for your chosen platform (e.g., Heroku).
