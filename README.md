## Project Structure
│
├── /src
|   |
|   |── /config
|   |   |── /db.config.js # Database configuration
|   |
│   ├── /controllers
│   │   ├── *.js # Handles task-specific-related AI operatinos
│   │
│   ├── /models
│   │   ├── /*_model      # Folder for task-specific model and logic
│   │   │   ├── train.js       # Training logic for task specific model
│   │   │   ├── model.json     # Saved model architecture
│   │   │   ├── weights.bin    # Trained model weights
│   │
│   ├── /routes
│   │   ├── *.js     # API routes for Task Specific
│   │
│   ├── /utils
│   │   ├── *.js     # For Functions that perform common tasks, such as formatting dates, parsing input data, or validating user input.
│   │
├── /data
│   ├── *.csv       # Dataset for training models
│
└── server.js                   # Main server file

## Requirements

- Node.js v18.20.4
- TensorFlow.js
- Express.js

## Installation
1. Clone the repository.
2. Install the required dependencies:
    npm install
    install visual studio installer
       - install Desktop Development C++
    install python v3.13
