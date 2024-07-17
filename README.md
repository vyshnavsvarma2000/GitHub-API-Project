# GitHub API Integration Project

This project demonstrates how to integrate with the GitHub API using Postman, covering CRUD operations and JSON Schema validation.

## Overview

This project uses Postman to interact with the GitHub API to perform basic CRUD operations on repositories. It includes examples of creating, reading, updating, and deleting repositories, along with validating API responses using JSON Schema.

## Prerequisites

Before running the Postman collection, make sure you have the following:

- Postman installed ([Download Postman](https://www.postman.com/downloads/))
- GitHub account and personal access token for authentication ([Creating a personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token))

## Setup

1. **Clone the Repository:**
   - Clone this GitHub repository to your local machine.

2. **Import the Postman Collection:**
   - Open Postman.
   - Click on `Import` button and select `Import From Link`.
   - Paste the following link to import the collection:
     ```
     https://www.getpostman.com/collections/your-collection-id
     ```
   - Replace `your-collection-id` with the actual collection ID from your Postman account.

3. **Set Environment Variables:**
   - In Postman, create a new environment or update the existing one.
   - Add the following variables:
     - `token`: Your GitHub personal access token.
     - `username`: Your GitHub username.

4. **Run the Requests:**
   - Run each request in the collection in the following order:
     - **Create Repository**: Create a new repository on GitHub.
     - **Get Repository Details**: Retrieve details of the created repository.
     - **Update Repository**: Update the repository name or description.
     - **Delete Repository**: Delete the repository from GitHub.

## Usage

- Open Postman and select the imported collection.
- Make sure the environment variables (`token` and `username`) are set correctly.
- Run each request and verify the results in the response body and status.

## JSON Schema Validation

JSON Schema validation ensures that the API responses conform to the expected structure. Each request in the collection includes a test script that validates the response against a predefined JSON Schema.

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to submit an issue or pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Report
![GitHubproject Report](https://github.com/user-attachments/assets/4c57e550-0fc4-444d-b097-c9e341642a03)
