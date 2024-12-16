# CodeFusion

**CodeFusion** is a cloud-based Integrated Development Environment (IDE) built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and Docker. It enables developers to code, collaborate, and manage projects directly from their browsers, eliminating the need for complex local setups.

---

## Features

- **Multi-Language Support**: Write, execute, and debug code in multiple programming languages.
- **Real-Time Collaboration**: Work seamlessly with teammates in real-time.
- **Cloud-Based Storage**: Save and access your projects from anywhere.
- **Docker Integration**: Ensure isolated, consistent, and scalable environments for every project.
- **User-Friendly Interface**: Intuitive UI built with React.js for a smooth user experience.
- **Secure Authentication**: User login and authentication handled securely using modern practices.

---

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Containerization**: Docker

---

## Installation

### Prerequisites

Ensure you have the following installed on your system:
- [Docker](https://www.docker.com/)
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/codefusion.git
   cd codefusion
   ```

2. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and configure the following:
   ```env
   PORT=5000
   MONGO_URI=mongodb://localhost:27017/codefusion
   JWT_SECRET=your_secret_key
   ```

3. **Install Dependencies**:
   ```bash
   # For Backend
   cd backend
   npm install

   # For Frontend
   cd ../frontend
   npm install
   ```

4. **Start the Application**:
   Using Docker Compose:
   ```bash
   docker-compose up --build
   ```

   Without Docker:
   ```bash
   # Start Backend
   cd backend
   npm start

   # Start Frontend
   cd ../frontend
   npm start
   ```

5. **Access the Application**:
   Open your browser and navigate to `http://localhost:3000`.

---

## Usage

1. **Sign Up/Login**: Create an account or log in to access the IDE.
2. **Create Projects**: Start a new project or continue working on an existing one.
3. **Collaborate**: Invite teammates to join your project and work together in real-time.
4. **Run and Debug Code**: Use the built-in terminal and code runner to execute your programs.

---

## Contributing

We welcome contributions to CodeFusion! To contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a Pull Request.

---

## License

CodeFusion is licensed under the [MIT License](LICENSE).

---
