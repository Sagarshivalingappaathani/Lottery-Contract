# Lottery Contract

## Project Overview

This project implements a simple Lottery smart contract on the Ethereum blockchain using Solidity. The contract allows users to participate in a lottery by sending Ether, and a random winner is selected and awarded the accumulated prize pool.

## Features

- **Participation:** Users can buy lottery tickets by sending Ether to the contract.
- **Prize Pool:** Ether sent for tickets accumulates in a prize pool.
- **Random Winner Selection:** A winner is randomly selected using a verifiable random number generator (VRNG).
- **Prize Distribution:** The winner receives the entire prize pool.

## Installation

1. **Install Node.js and npm:** If you don't have Node.js and npm installed, download and install the latest version from [https://nodejs.org/](https://nodejs.org/).

2. **Install Dependencies:** 
   ```bash
   npm install
   ```

## Usage

1. **Start a local blockchain:** 
   ```bash
   ganache-cli
   ```

2. **Compile the smart contract:**
   ```bash
   npm run compile
   ```

3. **Deploy the contract:**
   ```bash
   npm run deploy
   ```

4. **Run Tests:**
   ```bash
   npm run test
   ```