# frontend-react-redux-jwt
Creating a frontend using react, redux, jwt, locatStorage
### First Install
To skip the boilerplate I will use the commando below to start the project
    
    npx create-react-app frontend
    
Inside src folder create 3 folders:

        components: eg, navbar, sidebar, buttons,sliders
        screens:eg HomePage, PageNotfound etc
        services: get Data from api
        constants: store redux constants
        actions: redux actions
        reducers: redux reducers
        
        
Create React Components

        Header.js
        Footer.js
        ListItems.js
        AddItems.js
        Login.js
        Register.js
        Profile.js
        ForgetPassword.js
    
Things to understand:
    
        JSX
        React Router
        Props
        State
        Hooks
        Component Life Cycle
        Statemanagement
        Redux
        Virtual Dom
        Conditional Redering
        
        
### Second Install:
We are gonna need some packages and install material ui.

    yarn add axios react-redux @reduxjs/toolkit react-router-dom
    yarn add @mui/material @emotion/react @emotion/styled
    yarn add @mui/icons-material
    
    #to add date picker add followung
    ##yarn add @date-io/date-fns@1.3.13 @material-ui/pickers@3.3.10 date-fns@2.22.1
    yarn add @mui/x-date-pickers
    yarn add dayjs
    
    yarn add react-hook-form
    yarn add @material-ui/core

### Third Install:
Create Redux Store. This Store will bring Actions and Reducers together and hold the Application state.
Now we need to install Redux, Thunk Middleware and Redux Devtool Extension.
Run the command:

    yarn add redux redux-thunk
    yarn add redux-devtools-extension

### Fourth Installation:
Form Validation overview

    yarn add react-validation validator
