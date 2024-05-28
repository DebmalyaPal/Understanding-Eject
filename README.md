# Understanding-Eject

## Step 1 : `npx create-react-app eject-app`

This is the way we create a react app using CRA (create-react-app).<br>
To run this app : `cd eject-app` and then npm run OR `yarn start`.<br>
[This references scripts section inside `package.json`<br>
<br>
You can run several commands:<br>
A. Starts the development server :<br> 
&nbsp; npm start<br>
&nbsp; yarn start<br>
B. Bundles the app into static files for production :<br> 
&nbsp; npm run build<br>
&nbsp; yarn build<br>
C. Starts the test runner :<br> 
&nbsp; npm test<br>
&nbsp; yarn test<br>
D. Removes this tool and copies build dependencies, configuration files and scripts into the app directory :<br>
&nbsp; npm run eject<br>
&nbsp; yarn eject<br>
&nbsp; NOTE : If you do this, you can’t go back!<br>

## Step 2 : `npm eject`

Doing so will disclose all internal commands that react-scripts uses to do start, build, etc operations under the hood.
