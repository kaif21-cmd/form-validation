
---

# 📝 User Registration System with Node.js, Express, and MongoDB

This repository contains a simple user registration system built using Node.js, Express, and MongoDB. Users can register by providing their information, which is then stored in a MongoDB database. The system also includes static file serving for HTML, CSS, and JavaScript files.

## 🏛️ Jamia Hamdard

This project is developed as a part of studies at **Jamia Hamdard University**.<p align="center">
  <p align="center">
  <img style="border-radius: 50%;" width="150" alt="jamiahamdard" src="https://github.com/kaif21-cmd/form-validation/assets/85302180/772f5dda-0ff9-4efa-83bd-838090197c13">
</p>




## 📂 Folder Structure

The project follows the following folder structure:

```
user-registration-system/
│
├── public/            📁 Static files directory (HTML, CSS, JS)
│   ├── signup.html    📄 User registration form
│   ├── hsk.html       📄 Main application page
│   ├── styles.css     📄 Stylesheet
│   └── ...            📂 Other static files
│
├── index.js           📄 Main application file
├── package.json       📄 Node.js package configuration
└── LICENSE            📄 License information
```

## 🛠️ Languages and Technologies Used

- **Node.js**: JavaScript runtime for building the server-side application.
- **Express**: Web application framework for Node.js, used to create the server and handle routes.
- **MongoDB**: NoSQL database used to store user information.
- **HTML/CSS/JavaScript**: Used to create user interface components and client-side interactions.

## 🛠️ Tools Used

- **Visual Studio Code**: 💻 An integrated development environment (IDE) used for writing, debugging, and testing code.
- **MongoDB Compass**: 🧭 A GUI tool for MongoDB that provides a visual way to interact with and manage databases.

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- Node.js and npm (Node Package Manager): [Download & Install Node.js](https://nodejs.org/)
- Visual Studio Code: [Download & Install VS Code](https://code.visualstudio.com/)
- MongoDB Compass: [Download & Install MongoDB Compass](https://www.mongodb.com/products/compass)

### Installation

1. Clone this repository to your local machine:
   ```sh
   git clone https://github.com/your-username/user-registration-system.git
   ```
2. Navigate to the project directory:
   ```sh
   cd user-registration-system
   ```
3. Install the project dependencies:
   ```sh
   npm install
   ```

### Usage

1. Make sure MongoDB is installed and running on your machine.
2. Configure the MongoDB connection settings in the `index.js` file:
   ```javascript
   mongoose.connect("mongodb://127.0.0.1:27017/kaifshaikh12", { useNewUrlParser: true, useUnifiedTopology: true })
   ```
3. Start the application:
   ```sh
   npm start
   ```
4. Open a web browser and visit `http://localhost:8003` to access the application.

### Configuration

- You can change the port the server listens on by modifying the `port` variable in the `index.js` file:
   ```javascript
   const port = process.env.PORT || 8003;
   ```
- Ensure you follow best practices for storing sensitive data such as database connection strings. It's recommended to use environment variables or configuration files for such data.

### Contributing

Contributions are welcome! If you find any issues or want to enhance the application, feel free to submit a pull request.
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-feature`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Submit a pull request.


### License

This project is licensed under the [MIT License](LICENSE).

---
