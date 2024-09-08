Mini Project: House Price Prediction Model Deployment

For this project, I developed and deployed a Linear Regression model to predict house prices based on various input features. The deployment process was carried out using several tools and technologies, as detailed below:

1. Model Development:
I built a Linear Regression model using Python's Scikit-learn library to predict house prices based on a dataset of house features (e.g., number of bedrooms, square footage, location). After training and evaluating the model, I saved it for deployment purposes.

2. API Creation with Flask:
To make the model accessible via an API, I used the Flask framework to create a web service. This service allowed users to send house feature data as input and receive predicted prices in return. Flask was ideal for creating the lightweight backend for the API.

3. Using jsonify for Output:
The predicted house prices were returned in JSON format, using Flask's jsonify() function, making it easy for external applications to interact with the API.

4. Testing with Postman:
I tested the API endpoints using Postman, a tool that allows sending HTTP requests and verifying the API responses. This ensured the API was functioning correctly and returned accurate predictions.

5. Public Access with NGROK:
To expose the locally hosted API to the internet for broader accessibility, I used NGROK. NGROK generated a public URL for the Flask application, allowing external users or applications to interact with the API.

6. Development Environment:
The entire project was developed in Visual Studio Code (VS Code), which provided an efficient and powerful environment for writing Python code and managing the Flask application.

7. Conclusion:
By the end of the project, I successfully deployed a machine learning model as a web service, allowing predictions of house prices based on user input through an API. The deployment process demonstrated how machine learning models could be integrated into real-world applications using Flask, NGROK, and Postman.
