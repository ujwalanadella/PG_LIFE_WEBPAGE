# PG LIFE WEBPAGE

Welcome to the PG LIFE WEBPAGE project! This web application aims to provide a user-friendly platform for students looking for paying guest accommodations. It allows users to browse available PG options, filter based on their preferences, and connect with PG owners.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Registration and Login**: Users can create an account and log in to access additional features.
- **PG Listings**: Browse and search through a list of available PG accommodations.
- **Filter Options**: Users can filter PGs based on location, price, and amenities.
- **Contact Owners**: Directly contact PG owners for inquiries and bookings.
- **Responsive Design**: The application is designed to work seamlessly on both desktop and mobile devices.

## Technologies Used

This project utilizes the following technologies:

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Other Libraries**: [Add any other relevant libraries or frameworks used]

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ujwalanadella/PG_LIFE_WEBPAGE.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd PG_LIFE_WEBPAGE
   ```

3. **Install dependencies**:
   - For the backend:
     ```bash
     cd backend
     npm install
     ```
   - For the frontend (if applicable):
     ```bash
     cd frontend
     npm install
     ```

4. **Set up environment variables**:
   Create a `.env` file in the root of the backend directory and add the necessary environment variables (e.g., database URI, API keys).

5. **Start the application**:
   - For the backend:
     ```bash
     cd backend
     npm start
     ```
   - For the frontend (if applicable):
     ```bash
     cd frontend
     npm start
     ```

6. **Access the application**:
   Open your browser and navigate to `http://localhost:3000` (or the relevant port if specified).

## Usage

After setting up the project, you can start using the application:

1. **Register a new account** by clicking on the "Sign Up" button.
2. **Log in** using your credentials.
3. Browse through the available PG listings and use the filters to find your preferred accommodation.
4. Click on a listing for more details and use the contact form to reach out to PG owners.

## Project Structure

Here’s a brief overview of the project structure:

```
PG_LIFE_WEBPAGE/
│
├── backend/                # Backend server code
│   ├── models/             # Database models
│   ├── routes/             # API routes
│   ├── controllers/        # Request handling logic
│   ├── config/             # Configuration files
│   ├── .env                # Environment variables
│   └── server.js           # Main server file
│
├── frontend/               # Frontend code
│   ├── src/                # Source files
│   ├── public/             # Static files
│   ├── package.json         # Frontend dependencies
│   └── index.html          # Main HTML file
│
└── README.md               # Project documentation
```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

