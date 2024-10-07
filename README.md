# Python Pizza Calculator

A client-server application for calculating pizza prices based on size and toppings.

## Overview

This project consists of three main components:
1. GUI Client
2. Server
3. Database

The application allows users to select pizza size and toppings, then calculates the total price based on the selections.

## Features

- Select pizza size (Medium, Large, Extra Large)
- Choose from multiple toppings
- Real-time price calculation
- Reset functionality
- Client-server architecture for data management
- SQLite database for storing pricing information

## Components

### GUI Client

- Built using Tkinter
- Connects to the server to fetch pricing and topping data
- Provides an intuitive interface for pizza customization

### Server

- Handles client connections
- Retrieves data from the SQLite database
- Sends pricing and topping information to clients

### Database

- SQLite database (`pizza.db`)
- Contains tables for toppings and prices

## Setup

1. Ensure Python 3.x is installed on your system.
2. Install required dependencies:
   ```
   pip install tkinter
   ```
3. Set up the SQLite database using the provided database script.
4. Start the server by running the server script.
5. Launch the GUI client.

## Usage

1. Run the server script to start the server.
2. Launch the GUI client.
3. Select pizza size and toppings.
4. Click "Calculate Price" to see the total.
5. Use "Reset" to clear selections.

## Database Structure

- Toppings Table: Stores available toppings
- Prices Table: Stores prices for sizes and toppings

## Network Configuration

- The server listens on port 8685.
- Ensure the client and server are on the same network or configure appropriate port forwarding.

## Future Improvements

- Implement user authentication
- Add order history functionality
- Expand menu options
- Improve error handling and logging



## License

This project is licensed under the MIT License. See the LICENSE file for more details.
