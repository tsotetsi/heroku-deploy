This project(the server) was bootstrapped with [npm init](https://docs.npmjs.com/cli/init).

The client is a react application and was boostrapped using [npx create-react-app](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm run server`

Runs the app server in the development mode.<br />
Open [http://localhost:5000](http://localhost:5000) to view it in the browser. This normally works as the backend or API.

The page will reload if you make edits. Thanks to [nodemon](https://www.npmjs.com/package/nodemon)<br />
You will also see any lint errors in the console.

### `npm run client`

Launches the react client application.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser. This will be your client application.

### `npm run dev`

Runs both the server and the client. Thanks to concurrently module<br />
The request from the backend will be proxied to the right url and port.

### `npm run build`

Builds the client app for production in the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Deploying to Heroku

### `heroku login`

Login-in to heroku on your terminal. Assumes you already installed all the dependencies(cli, etc) and you are in the project root folder.

### `heroku create`

Create a heroku app. A url will be given to you and can be used to share with your friends or collegues.

### `git push heroku master`

Push you appplication to heroku and profit!

### `heroku logs --tail`

Check the logs on heroku in case something went wrong!.

