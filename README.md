# AE Assignment - Request Approval System

## Description

AE Assignment is a MERN (MongoDB, Express.js, React.js, Node.js) stack project that implements a Request Approval System. This system allows users to submit requests for approval and enables authorized users to review and approve or reject those requests.

## Prerequisites

Before you begin, ensure you have the following software installed on your machine:

- Node.js: Make sure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).

## Installation

1. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/ae-assignment.git
   ```

   Replace `your-username` with your GitHub username.

2. Navigate to the project directory:

   ```bash
   cd ae-assignment
   ```

3. Install server dependencies:

   ```bash
   npm install
   ```

4. Navigate to the client directory:

   ```bash
   cd client
   ```

5. Install client dependencies:

   ```bash
   npm install
   ```

6. Go back to the project root directory:

   ```bash
   cd ..
   ```

## Configuration

1. Create a `.env` file in the project root directory for server configuration. An example `.env` file might look like:

   ```
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/ae_assignment
   ```

   Modify the `MONGODB_URI` to point to your MongoDB instance.

2. Inside the `client` directory, create a `.env` file for client configuration. An example `.env` file might look like:

   ```
   REACT_APP_API_URL=http://localhost:5000
   REQUIRED_SECRET_KEY
   ```

   Modify the `REACT_APP_API_URL` to match your server's URL.

## Running the Application

1. In the project root directory, start the server:

   ```bash
   npm start
   ```

   This will start the Express.js server.

2. Open a new terminal window/tab, navigate to the `client` directory, and start the client:

   ```bash
   cd client
   npm start
   ```

   This will start the React development server.

3. Access the application in your web browser at [http://localhost:3000](http://localhost:3000).

## Usage

1. Log in to an existing account.
2. Submit a request for approval.
3. Authorized users can log in and review pending requests.
4. Approve or reject requests based on their details.
5. Users can view the status of their requests in their dashboard.

---

Feel free to customize this README with any additional information specific to your project. Good luck and happy coding!
