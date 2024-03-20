# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

## Run with Docker

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
