# CSTASK

## Description  
CSTASK is a simple C# application that starts an HTTP server and responds with "Hello World." It demonstrates the basics of building and deploying a C# application in Docker. This project is designed for ease of use, offering a quick setup for developers looking to experiment with Dockerized C# applications. It is accessible both online and locally through Docker, making it a great starting point for web app development in C#.

## Project Links  
- **Deployed on Docker Hub**: [2424833f/cstask](https://hub.docker.com/repository/docker/2424833f/cstask)
- **GitHub Repository**: [freddyelgato/CSTASK](https://github.com/freddyelgato/CSTASK)
- **Live Demo**: You can access the demo of the app at [http://localhost:8080](http://localhost:8080) once it's running locally.

## Getting Started 🚀

### Cloning the Repository  
To clone the repository, use the following command:  
`git clone https://github.com/freddyelgato/CSTASK.git`

### Navigate to the Project Directory  
Change to the project directory:  
`cd CSTASK`

### Building the Docker Image  
To build the Docker image for the application, use the following command:  
`docker build -t cstask .`

### Running the Application with Docker  
To run the application, execute:  
`docker run -p 8080:8080 --name CSTASK cstask`  
Once running, open your browser and visit [http://localhost:8080](http://localhost:8080) to view the "Hello World" message.

## Features ✨  
- Simple "Hello World" HTTP response.
- Dockerized for easy deployment and portability.
- Minimal setup for learning purposes.
- Works locally or can be deployed through Docker Hub.

## Advanced Usage 🌐  
If you wish to run the container on a different port, simply modify the port mapping. For example, to run it on port 3000, use:  
`docker run -p 3000:8080 --name CSTASK cstask`

## Additional Commands 🔧  
Here are some additional commands you might find useful:

### Stopping the Container  
To stop the running container, use:  
`docker stop CSTASK`

### Removing the Container  
To remove the stopped container:  
`docker rm CSTASK`

### Restarting the Container  
To restart the container after stopping it:  
`docker start CSTASK`

## Contributing 🤝  
We welcome contributions! If you want to add new features, report bugs, or improve documentation, please open an issue or submit a pull request in the [GitHub repository](https://github.com/freddyelgato/CSTASK).


## Support 💬  
If you encounter any issues or have questions, feel free to open an issue on the [GitHub repository](https://github.com/freddyelgato/CSTASK).  
For more information, check out the [Docker Hub page](https://hub.docker.com/repository/docker/2424833f/cstask).
