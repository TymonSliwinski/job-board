# Job board  

## Description  
This project is a platform that allows users to log in either as company, posting job offers, or as developer, applying to them.  
The project, as of now, consists of two parts:  
- Backend: REST API service written in Node.js, using Express.js  
- Mobile App: React Native app, using Expo  
  
## Usage  
### Backend  
1. Clone the repository `git clone https://github.com/TymonSliwinski/job-board.git`  
2. Create `.env` file in root directory, based on `.env.example`  
3. Run `docker compose --env-file .env up -d` to start database and backend containers  
  
### Mobile App  
1. Clone the repository `git clone https://github.com/TymonSliwinski/job-board-mobile.git`  
2. Run `npm install` to install dependencies  
3. Create `.env` file in `job-board-mobile` directory, with `BACKEND_URL` variable set to the address of the backend service  
4. Run `npm start` to start the app  
