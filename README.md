# potato-disease-classification-gcp

To deploy an ML model for potato disease classification in Google Cloud using AMD instance, follow the steps below:

Step 1: Create a Google Cloud account and sign in to the console.

Step 2: Create an AMD instance in Google Cloud.

Step 3: Install the necessary libraries and dependencies for the ML model. You can use pip or conda to install the required packages. Some of the essential packages are TensorFlow, Keras, NumPy, and Scikit-learn.

Step 4: Upload the trained ML model to the instance.

Step 5: Create a Flask application to serve the ML model as a RESTful API. You can use any web framework, but Flask is a lightweight and easy-to-use framework. Create an endpoint for the ML model to receive requests and send responses.

Step 6: Deploy the Flask application to the instance. You can use any WSGI server like Gunicorn to serve the Flask application.

Step 7: Set up a domain name for the Flask application, and configure HTTPS using a TLS certificate.

Step 8: Test the deployed ML model by sending a request to the endpoint.
