## Features

- **Add Expense**: Allows users to add an expense with different split methods.
- **Split Methods**:
  - **Equal Split**: The total amount is divided equally among all participants.
  - **Exact Split**: Users can specify how much each participant owes.
  - **Percentage Split**: Users can specify the percentage of the total amount each participant should pay.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Durgesh-kodan/nodejs-backend.git

   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Set up the database configuration in `config/db.js`.

4. Run the server:
   ```bash
   npm run dev
   ```

## Technologies Used

- Node.js: JavaScript runtime for building the server.
- Express: Web framework for Node.js.
- MongoDB: NoSQL database for storing expense data.
- Mongoose: ODM library for MongoDB and Node.js.
