## Setup for ReactJS + Running the frontend

1. Install Nodejs ([Setup instructions](https://nodejs.org/en/download/package-manager/))
2. Install NPM ([Setup instructions](https://www.npmjs.com/get-npm))
3. Install dependencies

```bash
cd lampara-nurse-scheduler
yarn install
```

4. Run the code
```bash
yarn dev
```

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Setup for Node/ExpressJS + Running the backend

### Prerequisites

Run the following command to install dependencies:

```shell
yarn install
```

### Setting up .env file

This project relies on specific environment variables. If you're running the project on your local machine, establish a .env file at the project's root to configure these variables. If using a hosting provider, utilize their built-in feature to directly set these variables, ensuring they are not inadvertently exposed. The necessary variables are as follows:

```
PORT=3000
DB_URL=mongodb://lampara-admin:lampara-admin@ac-unjezsj-shard-00-00.uxpqe43.mongodb.net:27017,ac-unjezsj-shard-00-01.uxpqe43.mongodb.net:27017,ac-unjezsj-shard-00-02.uxpqe43.mongodb.net:27017/?ssl=true&replicaSet=atlas-6u5zf6-shard-0&authSource=admin&retryWrites=true&w=majority
TOKEN_SECRET=vQGJTzp6dVO3tQaP5TE593vShCaUWLKBlC/0hnycBryobczMIR4nRjlqhOtz5yD6
```

After setting up .env file

Run the backend 

```shell
yarn start
```


