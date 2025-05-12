# FindaDoctor

A MERN stack application for searching doctors and booking appointments.

## Project Structure
- `app/FindaDoctor-FE/`: React frontend
- `app/FindaDoctor-BE/`: Node.js/Express backend
- `Dockerfile` (in each folder): For containerizing the app

## Prerequisites
- Node.js 18.x
- MongoDB (local or Atlas)
- Docker (for containerization)

## Running Locally
### Backend
```bash
cd app/FindaDoctor-BE
npm install
echo "MONGODB_URI=<your-mongodb-uri>" > .env
node index.js