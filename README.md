# bootcamp project
# Requirements
 * Node 12
 * Visual Studio Code

## Init the React frontend
npx create-react-app frontend
cd frontend
npm install react-router-dom http-proxy-middleware --save

## Clean up samples

## Init the React backend
mkdir backend
cd backend
npm init
npm install express body-parser --save
npm install nodemon --save-dev
add to package.json -> "scripts":
    "start": "node ."
    "start-dev": "nodemon ."

## set up dev environment
cd backend
npm run start-dev