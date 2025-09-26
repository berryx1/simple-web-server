# simple-web-server
A basic web server built using Docker and Nginx.

## Description
This project demonstrates how to create a simple web server using Docker and Nginx. It serves a static HTML page that displays "Hello, World!".


## Usage
                                               
2. Build the Docker image: `docker build -t simple-web-server .`
3. Run the Docker container: `docker run -p 8080:80 simple-web-server`
4. Open a web browser and navigate to `http://localhost:8080`

## Project Structure
* `Dockerfile`: The file that defines the Docker image
* `index.html`: The static HTML page served by the web server

## Technologies Used
* Docker
* Nginx
* HTML/CSS


