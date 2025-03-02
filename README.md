# Hospital Management System

This project is a hospital management system built using the MERN stack (MongoDB, Express, React, Node.js). It allows users to manage hospital information, including adding, updating, and deleting hospitals, as well as viewing detailed information about each hospital.

## Project Structure

The project is structured as follows:

```
.
├── .gitignore
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── README.md
├── vite.config.js
├── public/
│   └── vite.svg
├── server/
│   ├── server.js
│   ├── controllers/
│   │   └── hospitalController.js
│   ├── models/
│   │   └── Hospital.js
│   └── routes/
│       └── hospitalRoutes.js
└── src/
    ├── App.css
    ├── App.jsx
    ├── index.css
    ├── main.jsx
    ├── api/
    │   └── hospitalApi.js
    ├── assets/
    │   └── react.svg
    ├── components/
    │   ├── Alert.jsx
    │   ├── ConfirmationModal.jsx
    │   ├── HospitalCard.jsx
    │   ├── Navbar.css
    │   └── Navbar.jsx
    └── pages/
        ├── CreateHospital.css
        ├── CreateHospital.jsx
        ├── EditHospital.css
        ├── EditHospital.jsx
        ├── Home.css
        ├── Home.jsx
        ├── HospitalDetails.css
        ├── HospitalDetails.jsx
        ├── HospitalList.css
        └── HospitalList.jsx
```

## File Descriptions

### Root Files

- **.gitignore**: Specifies files and directories to be ignored by Git.
- **eslint.config.js**: ESLint configuration file.
- **index.html**: Main HTML file for the application.
- **package-lock.json**: Lock file for npm dependencies.
- **package.json**: Project metadata and dependencies.
- **README.md**: Project documentation.
- **vite.config.js**: Vite configuration file.

### Public Directory

- **vite.svg**: Vite logo used in the application.

### Server Directory

- **server.js**: Main server file using Express and Mongoose.
- **controllers/hospitalController.js**: Controller functions for hospital-related operations.
- **models/Hospital.js**: Mongoose model for the Hospital schema.
- **routes/hospitalRoutes.js**: Express routes for hospital-related endpoints.

### Source Directory

- **App.css**: Global CSS for the application.
- **App.jsx**: Main React component.
- **index.css**: Global CSS for the application.
- **main.jsx**: Entry point for the React application.
- **api/hospitalApi.js**: API functions for hospital-related operations.
- **assets/react.svg**: React logo used in the application.
- **components/Alert.jsx**: Alert component.
- **components/ConfirmationModal.jsx**: Confirmation modal component.
- **components/HospitalCard.jsx**: Hospital card component.
- **components/Navbar.css**: CSS for the Navbar component.
- **components/Navbar.jsx**: Navbar component.
- **pages/CreateHospital.css**: CSS for the CreateHospital page.
- **pages/CreateHospital.jsx**: CreateHospital page component.
- **pages/EditHospital.css**: CSS for the EditHospital page.
- **pages/EditHospital.jsx**: EditHospital page component.
- **pages/Home.css**: CSS for the Home page.
- **pages/Home.jsx**: Home page component.
- **pages/HospitalDetails.css**: CSS for the HospitalDetails page.
- **pages/HospitalDetails.jsx**: HospitalDetails page component.
- **pages/HospitalList.css**: CSS for the HospitalList page.
- **pages/HospitalList.jsx**: HospitalList page component.

## Dependencies

- **axios**: Promise-based HTTP client for the browser and Node.js.
- **cors**: Middleware for enabling CORS.
- **dotenv**: Module that loads environment variables from a `.env` file into `process.env`.
- **express**: Fast, unopinionated, minimalist web framework for Node.js.
- **mongoose**: MongoDB object modeling tool designed to work in an asynchronous environment.
- **react**: JavaScript library for building user interfaces.
- **react-dom**: Entry point to the DOM and server renderers for React.
- **react-router-dom**: DOM bindings for React Router.
- **vite**: Next generation frontend tooling.

## Development

To run the project locally, follow these steps:

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Start the development server using `npm run dev`.

## License

This project is licensed under the MIT License.

## Author

- **GitHub Username:** shekharshakti
- **Name:** shekhar shakti

