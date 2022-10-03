# gmailClone

You can view the demo [here](https://g-mail-30cd0.web.app/)

### clone the project

You can clone the project to your local computer.

- In your preffered folder, open your terminal and type the command

`` git clone https://github.com/Mykmicheals/gmailClone.git ``

- After cloning the project unzip the folder

- Navigate to the folder using

`` cd gmail_clone ``

- Install all dependencies using

`` npm install ``

- to run project on your localhost use the command

`` npm start ``

### The UI

![gmailClone](https://user-images.githubusercontent.com/88559940/193569460-69b6d176-357c-4f25-9b0d-a2f05cbf44ca.png)

![responsive](https://user-images.githubusercontent.com/88559940/193569807-82ec99d4-39c8-4c3d-9546-5ab81923aae6.png)

![compose](https://user-images.githubusercontent.com/88559940/193569826-66f6dcd0-2f90-4814-9625-92df91cdcebe.png)


### Project file structure

- Public folder. This is a very important folder in our app. This folder contains the index.html file and the manifest.json file.
The manifest. json provides information about a web application in a JSON text file, necessary for the web app to be downloaded and be presented to the user similarly to a native app 

- src folder. The src folder contains the various react components and the styled components neccessary for the website. The re-usable components are also stored in the src folder

![src](https://user-images.githubusercontent.com/88559940/193567603-08b93707-fc8a-4bc4-b3ca-5b7a6c95788e.png)

- Redux folder. The redux folder is used to store state managed for the webapp. They are various independent states managed in the website
![redux](https://user-images.githubusercontent.com/88559940/193568012-084b0b6f-821a-40c9-ba35-dc1f11dca6ea.png)

- package.json file
The package.json file contains neccessary configurations for the webapp. The file contains the various scripts and dependencies to make our webapp function properly

![dependencies](https://user-images.githubusercontent.com/88559940/193568472-24d6e968-15e7-41a7-8371-2cad095d333b.png)


### Key Technologies

- React
- Redux
- Redux-logger
- styled-components
- react-icons
- reselect
- react-router-dom

## React

React is the frontend javascript library used to build this gmail clone. React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. 


## Redux

Redux was used to manaage the entire state of the website. 

![reduxGmail](https://user-images.githubusercontent.com/88559940/193563059-064dab32-916e-4ede-9209-3fd1ed2af57d.png)

- Created a redux store
- Created different files to handle state updates
- Subscribed to different state updates

### Redux Logger

redux logger is a production Redux logging tool that lets you replay problems as if they happened in your own browser. Its a great debugging tool finding errors within our website.  It's an extension that tracks the application's state changes. You can trace, jump, skip any action that has been dispatched

### Styled Components

i used styled components to style our react app. Styled-components is a CSS-in-JS styling framework that uses tagged template literals in JavaScript and the power of CSS to provide a platform that allows you to write actual CSS to style React components.

![styledComponent](https://user-images.githubusercontent.com/88559940/193564683-b29163db-7a9a-4d6b-99f6-70db16f22f9b.png)

### Reselect

I used Reselect to compose selectors and the memoization can prevent expensive selector code from running. The memoization can also prevent needless re renders. What you should consider is maintainable code and with reselect you can write selector logic once and re use it by composing selecto

### Dependencies

-  react": "^18.0.0",
-    react-dom": "^18.0.0",
-    react-icons": "^4.4.0",
-    react-redux": "^8.0.2",
-    react-router-dom": "^5.3.3",
-    react-scripts": "^5.0.1",
-    redux": "^4.2.0",
-    redux-logger": "^3.0.6",
-    reselect": "^4.1.6",
-    styled-components: ^5.3.5
