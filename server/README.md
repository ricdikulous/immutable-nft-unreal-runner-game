# Immutable NFT Unreal Runner Game

This directory contains the Express.js server for the NFT Runner game. The server handles retrieving and returning player NFTs as well as minting functionality.

## Prerequisites

- **Node.js**: Ensure you have Node.js installed.
- **Environment Variables**: Set up the required environment variables by copying the `.env.example` file and filling in your own values.

## Environment Variables

Copy the `.env.example` file to `.env` and fill in the following values:

```plaintext
PRIVATE_KEY=
CONTRACT_ADDRESS=

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
S3_BUCKET_NAME=
S3_REGION=
```

## Setting Up the Server

Install the dependencies:

```sh
npm install
```

Start the server:

```sh
npm run dev
```

By default, the server runs on port 3000.

### API Documentation

Swagger is configured for this server. To view the API documentation, go to http://localhost:3000 in your browser.

### Server Endpoints

- **GET `/nfts/{address}`**: Endpoint for retrieving NFTs owned by a specific address.
- **POST `/mint`**: Endpoint for minting NFTs.