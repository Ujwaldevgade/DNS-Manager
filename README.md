# DNS Manager

DNS Manager is a full-stack application for managing DNS records and domains. It provides a user-friendly interface to create, update, and delete DNS records and domains.

## Features

- User authentication and authorization
- Dashboard to view all domains and DNS records
- Create new DNS records and domains
- Edit and delete existing DNS records and domains
- Visual representation of DNS data with charts
- Search and filter functionality
- Responsive design for mobile and desktop devices

## Technologies Used

- Frontend: React, React Router, Axios, Chart.js, React Icons, React Hot Toast
- Backend: Node.js, Express, MongoDB, Mongoose, JSON Web Tokens (JWT)
- Other: Vite (Frontend development server), Git (Version control), Vercel (Hosting), AWS Route 53 (DNS management)

## Setup Instructions

1. Clone the repository: `git clone https://github.com/Ujwaldevgade/DNS-Manager.git`
2. Navigate to the project directory: `cd DNS-Manager`
3. Install dependencies:
   - Frontend: `cd frontend && npm install`
   - Backend: `cd backend && npm install`
4. Configure environment variables:
   - Backend: Create a `.env` file in the `backend` directory and add necessary environment variables (e.g., MongoDB URI, JWT secret, AWS credentials)
5. Start the development servers:
   - Frontend: `cd frontend && npm start`
   - Backend: `cd backend && npm start`
6. Access the application at `http://localhost:3000` in your browser.

## Folder Structure

- `frontend`: Contains the React frontend code
- `backend`: Contains the Node.js backend code
- `docs`: Documentation files, including this README.md
- `screenshots`: Screenshots of the application

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
