# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

## Run with Docker manually

- In your terminal, navigate to the root directory of your React project and run:

  ```sh
  docker build -t my-react-app .
  ```

- Start the container using the following command, replacing my-react-app with your preferred name:

  ```sh
  docker run -p 5173:5173 --name my-react-app my-react-app
  ```

  #### Explanation of the Run Command:

  `-p 5173:5173`: Maps port 5173 inside the container to port 5173 on your Mac, allowing access from your browser.

  `--name my-react-app`: Assigns a name (my-react-app) to the container for easier management.

## Run with Docker compose

- Build and Run the Container

  Execute the following command to build the Docker image for your React app and start the container in detached mode (running in the background):

  ```sh
  docker compose up -d
  ```

  `docker-compose up`: This instructs Docker Compose to build and bring up the services defined in your docker-compose.yml file.

  `-d`: The -d flag specifies detached mode, allowing the container to run in the background without attaching to your terminal session.

- Stop the Container

  When you're finished developing and want to stop the container, use this command:

  ```sh
  docker compose stop
  ```

  This will gracefully stop the container without affecting its data or configuration.
