# Immutable NFT Unreal Runner Game

This repository contains the complete codebase for the NFT Runner game, including the server, game logic, and AWS CDK infrastructure. The game is an endless runner built in Unreal Engine 5.2 using Blueprints, integrated with Immutable's SDK for NFT functionality. It covers player authentication via Immutable Passport, NFT minting, and displaying NFTs within the game.

## Repository Structure

- **Game**: Contains the Unreal Engine 5.2 project files for the NFT Runner game.
- **Server**: Contains the Express.js server code, responsible for handling player NFTs and minting functionality.
- **Infrastructure**: Contains AWS CDK code for deploying a publicly readable S3 bucket for storing metadata for the smart contract and individual NFTs.

## Prerequisites

- **Git LFS**: Ensure you have Git LFS installed to clone the repository.
- **Unreal Engine 5.2**: The game project requires Unreal Engine version 5.2.
- **Node.js**: Required to run the Express.js server.
- **AWS CLI and CDK**: Required to deploy the infrastructure.
