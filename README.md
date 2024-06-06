# Getting Started with Create React App

NOTE: This project is just a warmup and is not a bussiness plan or anything related for work at all. All HTML and CSS codes are premade and I just used them to practise my own Reactjs skill.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm run server`

The following code in package.json must run before you fireup the project ... make sure the port 9000 is free for this server.
If there is any issue running on this port feel free to change it. Keep in mind that you have to change it in src/contexts
/QuizContext.js file as well.

    "server": "json-server --watch data/questions.json --port 9000"
