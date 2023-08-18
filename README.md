# Backend API Technical Task: Online Application Form

Welcome to the Backend Developer recruitment challenge for the position at Cairo University Eco-Racing Team. This task is designed to assess your skills in designing and implementing a backend API using Python FastAPI, creating an ER model, and performing testing using tools like Postman. Please carefully follow the instructions below to complete the task.

## Task Overview

In this challenge, you will be responsible for designing and implementing a backend API to support an online application form. You will use Python FastAPI to create the API endpoints and handle application data. Additionally, you will design an Entity-Relationship (ER) model to represent the data structure of the application form. Lastly, you will use Postman to thoroughly test the functionality of the API endpoints.

## Instructions

### Part 1: Backend API Implementation

1. Clone this repository to your local machine.
2. Create a new branch named `backend-api`.
3. Build a FastAPI-based backend API with the following endpoints:

   - `POST /applications`: Accept application data and store it in the database.
   - `GET /applications`: Retrieve a list of all submitted applications.
   - `GET /applications/{application_id}`: Retrieve details of a specific application by ID.
   - `PUT /applications/{application_id}`: Update an existing application's data.
   - `DELETE /applications/{application_id}`: Delete a submitted application.

4. Ensure appropriate error handling, validation, and data storage for the API.
5. Write clear and concise code comments.
6. Commit your changes and push the branch to this repository.

### Part 2: ER Model Design

1. Design an ER model for the online application form's data structure.
2. Capture relevant entities, attributes, and relationships in the ER diagram.
3. You can choose either a NoSQL or SQL approach for data modeling.
4. Include an image or PDF of the ER model diagram in the repository.

### Part 3: Postman Testing

1. Install Postman (if not already installed) from [postman.com](https://www.postman.com/downloads/).
2. Test each of the API endpoints and create a collection.
3. Ensure that the requests return the expected responses.
4. Capture detailed screenshots of your Postman tests for each API endpoint.
5. Commit the screenshots to the repository.

## Submission

Once you have completed the tasks, create a pull request from your `backend-task` branch to the `master` branch of this repository. In the pull request description, provide a brief overview of your approach, any challenges faced, and any additional notes you'd like to share.

### Evaluation Criteria

Your submission will be evaluated based on the following criteria:

- **Functionality:** Does the API meet the specified requirements? Does it handle errors and validation properly?
- **Code Quality:** Is the FastAPI code well-organized, readable, and adequately commented?
- **ER Model:** Is the ER model well-designed and accurately represents the data structure?
- **Postman Testing:** Are the Postman tests comprehensive and do they cover all API endpoints?

Feel free to reach out in github issues if you have any questions or need clarification on the tasks. Good luck!

---
## README.md Template

Please fill in the following information in the `README.md` file of your repository:

### ER Model Diagram

Please include an image or PDF of your ER model diagram here.

### Screenshots

Please use the following template to capture detailed screenshots of your Postman tests:

#### API Endpoint 1: Create an application

![Create Application](screenshots/create_application.png)

#### API Endpoint 2: Retrieve list of applications

![Get Applications](screenshots/get_applications.png)

#### API Endpoint 3: Retrieve a specific application

![Get Application](screenshots/get_application.png)

#### API Endpoint 4: Update an application

![Update Application](screenshots/update_application.png)

#### API Endpoint 5: Delete an application

![Delete Application](screenshots/delete_application.png)

## Author

[Your Name]

---

**Note:** Replace `[Your Name]` with your actual name.
