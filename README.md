# special-octo-enigma
## Project Description
The special-octo-enigma project is a Python application that connects to a MongoDB Atlas cluster using environment variables.
## What it Does
This project provides a simple way to connect to a MongoDB Atlas cluster and retrieve a list of available databases.
## Key Features
* Connects to MongoDB Atlas using environment variables
* Retrieves a list of available databases
* Handles connection errors and configuration errors
## Tech Stack
* Python 3.x
* PyMongo library
* MongoDB Atlas
## Installation
To install the required libraries, run the following command:
```bash
pip install pymongo
```
## Usage
To use this project, simply run the App.py file:
```bash
python App.py
```
## Required Environment Variables
The following environment variables are required:
* MONGODB_ATLAS_USERNAME
* MONGODB_ATLAS_PASSWORD
* MONGODB_ATLAS_CLUSTER
These variables should be set to your MongoDB Atlas cluster credentials.
## Example Usage
To set the environment variables, you can use the following commands:
```bash
export MONGODB_ATLAS_USERNAME=your_username
export MONGODB_ATLAS_PASSWORD=your_password
export MONGODB_ATLAS_CLUSTER=your_cluster
```
Then, run the App.py file to connect to your MongoDB Atlas cluster.