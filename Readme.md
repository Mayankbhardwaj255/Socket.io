# Socket.IO Demo Repository

This repository demonstrates how Socket.IO works with a simple client-server setup. The project contains two main directories:

- **client/** - The frontend implementation.
- **server/** - The backend implementation.

## Getting Started

### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Installation

1. **Clone the Repository**
   ```sh
   git clone https://github.com/Mayankbhardwaj255/Socket.io.git
   cd your-repo-name
   ```

2. **Install Dependencies**
   Navigate to the `server` and `client` folders and install the required dependencies:

   ```sh
   cd server
   npm install
   ```
   
   ```sh
   cd ../client
   npm install
   ```

### Running the Application

1. **Start the Server**
   ```sh
   cd server
   npm run dev
   ```

2. **Start the Client**
   ```sh
   cd client
   npm run dev
   ```

3. **Login to Enable Socket.IO Functionality**

Once both servers are running, visit http://localhost:3000/login in your browser to log in.
Authentication is handled using JWT and cookies, and logging in is required to access real-time features powered by Socket.IO.

After logging in, you can begin using the real-time features provided in this demo.

The application should now be running, and you can interact with it through the frontend.

## Technologies Used
- **Socket.IO** - For real-time communication
- **Express.js** - Backend framework
- **React.js** (or any frontend framework used) - For the frontend interface

## Contributing
Feel free to fork this repository and submit pull requests with improvements or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
**Happy coding!** 🚀

