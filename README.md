# Store for Video Games

Welcome to the **Store for Video Games** project! This repository contains the code and resources for creating a video game store website where users can browse, search, and purchase their favorite video games.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The **Store for Video Games** is a web application designed to provide users with an engaging and user-friendly interface to explore and buy video games. This project aims to simulate a real-world e-commerce platform tailored specifically for video game enthusiasts.

## Features

- **User Authentication**: Sign up, log in, and log out functionality.
- **Game Catalog**: Browse a wide range of video games with detailed information.
- **Search Functionality**: Search for games by name, genre, or platform.
- **Shopping Cart**: Add games to the cart and proceed to checkout.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend**:
  - HTML5
  - CSS3
  - JavaScript
  - React.js

- **Backend**:
  - Node.js
  - Express.js

- **Database**:
  - MongoDB

- **Version Control**:
  - Git

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/StephenSouth13/stephensouth-store-for-videos1games.git
    cd stephensouth-store-for-videos1games
    ```

2. **Install dependencies**:

    For the backend:

    ```bash
    cd backend
    npm install
    ```

    For the frontend:

    ```bash
    cd ../frontend
    npm install
    ```

3. **Set up environment variables**:

    Create a `.env` file in the backend directory and add the following:

    ```env
    PORT=5000
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_secret_key
    ```

4. **Run the application**:

    Start the backend server:

    ```bash
    cd backend
    npm start
    ```

    Start the frontend development server:

    ```bash
    cd ../frontend
    npm start
    ```

    Open your browser and navigate to `http://localhost:3000`.

## Usage

- **Browse Games**: Navigate through the game catalog to find interesting games.
- **Search Games**: Use the search bar to find games by specific criteria.
- **Add to Cart**: Select games and add them to your shopping cart.
- **Checkout**: Proceed to checkout to purchase the selected games.

## Contributing

We welcome contributions from the community! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

Please ensure your code adheres to our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

If you have any questions or feedback, feel free to reach out:

- **Name**: Stephen South
- **Email**: stephensouth@example.com
- **GitHub**: [StephenSouth13](https://github.com/StephenSouth13)

Thank you for visiting the **Store for Video Games** project! We hope you enjoy using it as much as we enjoyed building it.
