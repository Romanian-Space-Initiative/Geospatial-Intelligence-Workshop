# Web App with TIFF Image Viewer

This repository contains a simple web application built with Flask that serves as a TIFF image viewer. The application allows users to view a TIFF image and provides zoom functionality using a web interface.

## Prerequisites

Before running the code, make sure you have the following technologies installed on your computer:

- **Docker:** Install Docker on your machine by following the instructions provided [here](https://docs.docker.com/get-docker/).

## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/Romanian-Space-Initiative/Geospatial-Intelligence-Workshop.git
    cd Geospatial-Intelligence-Workshop
    ```

2. Build the Docker image:

    ```bash
    docker-compose build
    ```

3. Run the Docker container:

    ```bash
    docker-compose up
    ```

4. Open your web browser and navigate to [http://localhost:5001](http://localhost:5001) to access the TIFF Image Viewer.

## Project Structure

- **webapp/Dockerfile:** Defines the Docker image for the application.
- **webapp/docker-compose.yml:** Configuration for Docker Compose, specifying service details.
- **webapp/deploy.sh:** Deployment script that converts TIFF to JPEG and starts the Flask application.
- **webapp/app.py:** Flask application file with a simple route for rendering the web interface.
- **webapp/templates/index.html:** HTML template for the TIFF Image Viewer web interface.
- **webapp/static/jpg:** Directory containing the converted JPEG image.
- **webapp/static/tiff:** Directory containing the original TIFF image.

## Notes

- The Docker container exposes the application on port 5001. You can change the port in the `docker-compose.yml` file if needed.
- The zoom functionality on the web interface is implemented using JavaScript.

Feel free to explore and modify the code as needed for your use case. If you encounter any issues, please check the [issues](https://github.com/your-username/your-repo/issues) section of this repository or open a new issue.

Happy coding!
