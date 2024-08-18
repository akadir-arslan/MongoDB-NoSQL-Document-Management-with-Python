# MongoDB(NoSQL document database) Document Management with Python

## Overview

This project demonstrates the use of MongoDB, a NoSQL document database, for managing and manipulating JSON-style documents. It covers the entire workflow from installation and configuration to programming and data operations using Python.

## Installation and Setup

1. **MongoDB Installation**: MongoDB was installed natively on a Windows operating system. A database named `first_database` and a collection named `first_collection` were created via the MongoDB GUI.

2. **Python Client Library**: The MongoDB Python Client Library (`pymongo`) was installed to interact with the MongoDB database programmatically.

## Project Details

1. **Database Connection**: Demonstrates how to connect to a MongoDB cluster using a connection string and verify successful connections.

2. **Data Ingestion**: Generates and inserts random JSON-style documents representing book data into the MongoDB collection. 

3. **Data Operations**:
   - **Insert**: Shows how to insert single and multiple documents into the database.
   - **Update**: Illustrates how to update specific documents, including conditional updates.
   - **Query**: Retrieves and displays documents based on specified criteria.
   - **Delete**: Demonstrates how to delete documents either individually or in bulk.

This project aims to provide a practical understanding of MongoDB’s capabilities in handling document-based data and performing essential CRUD (Create, Read, Update, Delete) operations.

## How to Run

1. **Install MongoDB**: Follow the installation instructions for MongoDB on your operating system. Ensure MongoDB is running before proceeding.

2. **Set Up Python Environment**:
   - Install the required Python library:
     ```bash
     pip install pymongo
     ```

3. **Configure the Connection**:
   - Update the connection string in the Python script or Jupyter notebook with your MongoDB connection details.

4. **Run the Code**:
   - Execute the provided Python script or Jupyter notebook to perform operations such as inserting, querying, updating, and deleting documents in the MongoDB database.

