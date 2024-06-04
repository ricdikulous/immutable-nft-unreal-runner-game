# Endless Runner Game with NFT Integration

This project demonstrates the integration of NFTs into an Unreal Engine game using Immutable's SDK. The game is an endless runner where players dodge obstacles and collect coins, with the ability to mint unique character NFTs based on in-game achievements.

## Quick Start

### Prerequisites

- Unreal Engine 5.2
- Node.js and a local server setup for handling NFT minting and retrieval

### Installation

1. Clone this repository and open the project file `endlessrun.uproject` in Unreal Engine.
2. Ensure the local server for NFT functionality is running (assumed to be running at `localhost:3000`).

### Run Game

- Open MainMenu at `/Content/Levels/MainMenu.umap`.
- Press the play button to start the game.

### Gameplay Functionality

- Players navigate a character who must dodge trees and collect coins.
- Hitting an obstacle ends the game, while collecting coins contributes to NFT minting eligibility.
- On collecting 10 coins, players can mint one of five unique character NFTs.
- Minted NFTs can be accessed and viewed within the game, enhancing player engagement and experience.

### NFT Integration

- **Login with Immutable Passport**: Authenticate to track and manage your NFTs.
- **Retrieving NFTs**: Access your minted NFTs via the game interface.
- **Minting NFTs**: Achieve in-game goals to mint NFTs automatically.

### Server Endpoints

- **GET `/nfts/{address}`**: Endpoint for retrieving NFTs owned by a specific address.
- **POST `/mint`**: Endpoint for minting NFTs.

