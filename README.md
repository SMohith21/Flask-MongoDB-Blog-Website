Flask-MongoDB-Blog-Website is a basic blog web application created using Flask, MongoDB, and Python. This application allows users to read, create, edit, and delete blog posts, as well as register and log in as administrators. The repository contains the source code for the application, including the necessary files to run it locally.

To get started with the application, you will need to have Python 3 installed on your machine. You will also need to install the required Python packages, which are listed in the requirements.txt file. Once you have installed the necessary packages, you can run the application by following these steps:

1. Clone the repository to your local machine.
2. Navigate to the root directory of the repository.
3. Build the Docker image by running the following command:

  `docker build -t flask-mongodb-blog-website`

4. Run the Docker container by executing the following command:

  `docker run -p 5000:5000 flask-mongodb-blog-website`

Open your web browser and navigate to `http://localhost:5000` to view the application.
