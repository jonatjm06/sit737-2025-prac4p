# sit737-2025-prac4p
SIT323/SIT737- Cloud Native Application Development Task 4.1P: Building a simple calculator microservice

# Calculator Microservice

## Introduction
This microservice is a simple REST API built with Node.js and Express that performs basic arithmetic operations (addition, subtraction, multiplication, and division). It also includes logging with Winston for monitoring requests and errors.

## Features
- RESTful API for basic arithmetic operations
- Error handling for invalid inputs and division by zero
- Logging using Winston
- API testing using Postman

## Prerequisites
Before running this microservice, ensure you have the following installed:
- Node.js (v14 or later)
- npm (Node Package Manager)
- Postman (optional for testing API endpoints)

## Installation and Setup
1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd sit737-2025-prac4p
   ```
2. **Initialize a new Node.js project:**
   ```sh
   npm init -y
   ```
3. **Install required dependencies:**
   ```sh
   npm install express winston axios
   ```
4. **Run the microservice:**
   ```sh
   node app.js
   ```

## Testing with Postman
1. Open Postman and create a new `POST` request.
2. Enter the API endpoint, e.g., `http://localhost:3000/add`.
3. Go to the **Body** tab and select **raw**, then choose **JSON**.
4. Enter the request payload (e.g., `{ "num1": 10, "num2": 5 }`).
5. Click **Send** and check the response.

