# Ayurvedic Diet Management Software

## Overview
The Ayurvedic Diet Management Software is a cloud-based application designed to help users manage their dietary needs based on Ayurvedic principles. The application provides personalized diet plans, nutritional summaries, and meal recommendations tailored to individual health requirements.

## Features
- User-friendly interface for managing diet plans.
- Integration of Ayurvedic dietary principles.
- Ability to create, read, update, and delete diet plans.
- Nutritional analysis of meals.
- Secure user authentication and data management.

## Technologies Used
- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express, TypeScript, PostgreSQL
- **Database**: PostgreSQL
- **Documentation**: Markdown

## Project Structure
```
ayurvedic-diet-management
├── backend
├── frontend
├── database
└── docs
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- PostgreSQL (v12 or higher)

### Installation

1. **Clone the repository**
   ```
   git clone <repository-url>
   cd ayurvedic-diet-management
   ```

2. **Backend Setup**
   - Navigate to the backend directory:
     ```
     cd backend
     ```
   - Install dependencies:
     ```
     npm install
     ```
   - Configure the database connection in `src/config/database.ts`.
   - Run the server:
     ```
     npm start
     ```

3. **Frontend Setup**
   - Navigate to the frontend directory:
     ```
     cd frontend
     ```
   - Install dependencies:
     ```
     npm install
     ```
   - Start the frontend application:
     ```
     npm start
     ```

### Database Setup
- Run the SQL scripts located in the `database/schema` and `database/migrations` directories to set up the initial database structure.

## Documentation
- For detailed API documentation, refer to `docs/api.md`.
- For architecture details, refer to `docs/architecture.md`.

## Contribution
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.