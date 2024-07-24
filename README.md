# Basic Node Express Wrapper

- You will need to run 'npm ci' in your pipeline to install the express dependency
- Copy your React build folder into 'frontend/build' (Optionally you can add your entire React App inside a 'frontend' directory if so desired and execute 'npm run build' from that directory.)
- The serve.js file uses a 'buildPath' constant to route all incoming requests to the index.html file in your build folder.
- The package.json contains a start script that will run the 'serve.js' file in a node environment using 'npm run start'.
