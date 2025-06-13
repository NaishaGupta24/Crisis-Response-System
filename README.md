# Smart Crisis Response System

## Overview

The Smart Crisis Response System is a web application designed to assist citizens and government officials in managing disaster-related information and resources. The application provides functionalities for reporting emergencies, accessing police and fire station information, and tracking submitted tickets.

## Features

- **Citizen Dashboard**: Allows citizens to report emergencies and access resources.
- **Official Dashboard**: Provides government officials with access to resources and ticket management.
- **Police Stations Information**: Displays a list of police stations with contact details.
- **Fire Stations Information**: Displays a list of fire stations with contact details.
- **Ticket Management**: Citizens can submit tickets for assistance, and officials can track these tickets.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Database**: MySQL
- **Libraries**: [MySQL2](https://www.npmjs.com/package/mysql2), [Express](https://expressjs.com/)

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/vibhor2608/Disaster-Management-Project.git
   cd disaster-management
   ```

2. **Install Dependencies**:
   Make sure you have Node.js and npm installed. Then run:
   ```bash
   npm install
   ```

3. **Set Up the Database**:
   - Create a MySQL database named `disaster_management`.
   - Run the SQL scripts provided in the project to create tables and insert initial data.

4. **Start the Server**:
   ```bash
   npm start
   ```

5. **Access the Application**:
   Open your web browser and navigate to `http://localhost:3000/citizen/dashboard.html` for the citizen dashboard or `http://localhost:3000/official/dashboard.html` for the official dashboard.

## Usage

- **For Citizens**: Use the citizen dashboard to report emergencies and access police and fire station information.
- **For Officials**: Use the official dashboard to manage resources and track submitted tickets.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to all contributors and resources that helped in the development of this project.