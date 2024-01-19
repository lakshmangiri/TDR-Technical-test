## TDR Technical Assessment
This repository contains the code for the TDR Technical Assessment project, consisting of a full-stack application with a React-based client-side and a Node.js/Express.js server-side, backed by a MongoDB database.

### Overview
* **Client-Side:** A React.js application that provides a user-friendly interface for interaction with the system. \
* **Back-End:** A Node.js server using Express.js to handle API requests and manage interactions with the MongoDB database.

### Installation and Setup
* Prerequisites
* Node.js
* MongoDB
* Git

#### Clone the Repository
First, clone the repository to your local machine:

```bash
git clone https://github.com/[your-username]/TDR-Technical-test.git
cd TDR-Technical-test
```
#### Submodules Setup
This project contains submodules for the client-side and back-end. After cloning the main repository, initialize and update the submodules using:

```bash
git submodule init
git submodule update
```

#### Client-Side Setup
Navigate to the client-side directory and install dependencies:

```bash
cd client-side
npm install
```

To run the React app:

```bash
npm start
```

#### Back-End Setup
Navigate to the back-end directory and install dependencies:

```bash
cd ../back-end
npm install
```

To start the server:

```bash
cd back-end
nodemon app.js
```

#### Usage
After starting both the client-side and back-end servers, open http://localhost:3000 in your browser to use the application.

#### Features
* View and Student Data displayed in a Table.
* Add new student records.
* Calculate and display academic averages and grades.



