From the root folder of this repo, run

```bash
yarn install # Install root dependencies (for TS & linting in your IDE)
cd packages/backend && yarn install # Install backend packages
cd ../frontend && yarn install # Install frontend packages
cd ../.. # Go back to root folder
yarn start # Will launch the frontend and the backend at the same time
```

The backend should be running on `localhost:8000`, and the frontend on `localhost:3000`.

Alternatively, you can start the frontend and the backend separately:

```bash
# Start the backend
cd packages/backend
yarn start

# Start the frontend
cd packages/frontend
yarn start
```

Reference: 
https://www.toptal.com/ethereum/one-click-login-flows-a-metamask-tutorial

