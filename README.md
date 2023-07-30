
# 📚 E-Learning Platform

The E-Learning platform is a web application built using Node.js, Express.js, Firebase Firestore, and Bootstrap. It allows users to sign up, sign in, and access educational content based on their preferences. This README provides detailed information about the project, including features, installation, configuration, project structure, usage, contributing guidelines, license, acknowledgments, and contact details.

## 🚀 Features

- **User Registration**: Users can sign up for the platform by providing their personal details, including first name, last name, email, password, date of birth, address, gender, pincode, and preferred course.

- **User Authentication**: The platform provides a secure login system where users can sign in using their email and password.

- **Access to Educational Content**: Upon successful login, users are directed to the home page where they can access various educational resources based on their preferences and selected course.
<!-- Project Showcase: Google Drive Link -->
 ## 📂 Project Showcase: 
  [View on Google Drive](https://drive.google.com/file/d/1iv-THgC5zasqw6eH0gKrZYFO7x0vuyfq/view?usp=share_link)
## ⚙️ Prerequisites

Before running the application, make sure you have the following installed:

- **Node.js**: Download and install Node.js from the official website (https://nodejs.org).

## 🔧 Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/e-learning-platform.git
   ```

2. Navigate to the project directory:

   ```bash
   cd e-learning-platform
   ```

3. Install the dependencies using npm:

   ```bash
   npm install
   ```

## 🔒 Configuration

Before running the application, you need to configure the Firebase service account credentials. Follow these steps:

1. Go to the Firebase Console (https://console.firebase.google.com/) and create a new project.

2. Go to the project settings and navigate to the "Service accounts" tab.

3. Click on "Generate new private key" to download the service account key file in JSON format.

4. Rename the downloaded file to `serviceAccountKey.json` and place it in the project root directory.

## ▶️ Usage

To start the server, run the following command:

```bash
npm start
```

The application will start running on `http://localhost:3000`. Open this URL in your web browser to access the E-Learning platform.

## 📁 Project Structure

- **app.js**: The main entry point of the application where the Express server is configured.

- **views/**: This directory contains the EJS templates for different pages, such as home, sign-in, sign-up, and dashboard.

- **public/**: This directory contains static assets (CSS, images, etc.) used in the front-end.

- **serviceAccountKey.json**: Firebase service account key file containing authentication credentials.

## 🤝 Contributing

Contributions are welcome! If you find any bugs or want to add new features, feel free to submit a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it. However, any usage with malicious intent is strictly prohibited.

## 🙏 Acknowledgments

- Thanks to the open-source community for their invaluable contributions.

- Special thanks to [Bootstrap](https://getbootstrap.com/) for providing an excellent front-end framework.

## 📬 Contact

Feel free to reach out to me via the following channels:

- **Email**: [mssannitya@gmail.com]
- **LinkedIn**: [https://www.linkedin.com/in/m-s-052080214/]

## 🌟 Let's Connect!

I'm always eager to collaborate on exciting projects or discuss interesting ideas. Connect with me, and let's create something awesome together!

Thank you for stopping by! ✨


🎉 Happy Learning! 🎓
