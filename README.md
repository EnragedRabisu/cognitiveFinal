### Setting up NPM dependencies
```bash
npm install
```

### Setting up global dependencies
Either add references to 'node-sass-chokidar' and 'react-scripts' to the PATH variable or do the following to install them globally:
```bash
npm install -g node-sass-chokidar
npm install -g react-scripts
```

### Setting up the React Front-end
Create an optimized build of your app. During this stage, your environment variable will be inserted into App.js for use by your components.
```bash
npm run build
```

### Running the App
All that's left is to serve your static files locally. You should see the app running in a new tab!
```bash
npm start
```

Example commands that can be executed by the Watson Assistant service are:
```
What is your purpose
I want to talk to the registrar
```
In addition to conversational commands, you can also ask questions that you would expect to have answered in your car manual. For example:
```
I need a C class
I am looking for a course with a MATH 220 prerequisite
```
## License
Licensed under [Apache 2.0](LICENSE).
