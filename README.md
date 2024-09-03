# DigiTrust ICP Integration

This project integrates DigiTrust with Internet Computer Protocol (ICP) canisters. It consists of two main components:

1. UI Application (`src/digitrust_icp_frontend` folder)
2. Canister Service (`src/digitrust_icp_backend` folder)

## Project Structure

- `src/digitrust_icp_frontend`: Contains the frontend UI application
- `src/digitrust_icp_backend`: Contains the backend canister code

## UI Application (app)

The `digitrust_icp_frontend` folder contains the frontend application built with React. It includes:

- Components
- Hooks
- Theme configuration
- Utility functions
- Localization support

## Canister Service (canister_service)

The `digitrust_icp_backend` folder contains the backend code for building and deploying ICP canisters. It includes:

- `dfx` configuration
- Canister source code
- Test files

## Setup and Running

To start the canister service:

```
cd digitrust_icp_backend
dfx start --clean --background
```

## Running test for DigiTrust

### Step 1: Start a local instance of the Internet Computer

```bash
dfx start --clean --background
```

### Step 2: Install npm dependencies

```bash
npm install
```

### Step 3: Run the test suite

```bash
make test
```
