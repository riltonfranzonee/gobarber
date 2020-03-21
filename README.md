
<h1 align="center">
    <img src="https://user-images.githubusercontent.com/58868651/77219318-88174b00-6b13-11ea-924d-1a6acdcbd939.png" />
</h1>

<p align="center">
Barbershop system that connects clients and providers - Web version made with ReactJS
</p>

💈 About GoBarber
------------------
This project is a system of a fictional barbershop called GoBarber. The full system has a [**web version**](https://github.com/riltonfranzonee/gobarber) made with ReactJS, an exclusive area for providers, where they are able to list all their appointments, change personal info and recieve notifications everytime a new appointment is created (also via email). The application also has a [**mobile version**](https://github.com/riltonfranzonee/gobarber-mobile) made with React Native, an exclusive area for clients, where they are able to create a new appointment with their favorite provider based on the available schedule. Besides that, the client is able to cancel the appointment (must be at most 2 hours before the appointment). All this system is served by a [**RESTful API**](https://github.com/riltonfranzonee/gobarber-api) made with Node.js.

<img alt="1" src="https://user-images.githubusercontent.com/58868651/77219064-d70fb100-6b10-11ea-9faf-f51cdcd0b45e.png">
<img alt="2" src="https://user-images.githubusercontent.com/58868651/77219066-d840de00-6b10-11ea-834b-3863c93b68e0.png">
<img alt="3" src="https://user-images.githubusercontent.com/58868651/77219067-d8d97480-6b10-11ea-8d63-e7967cce9051.png">
<img alt="4" src="https://user-images.githubusercontent.com/58868651/77219068-d9720b00-6b10-11ea-8ee7-502992bbdd6f.png">

:wrench: Used technologies:
----------------------
The web version of the application handles with a lot of data and information. To help me persist data and authenticate the provider I've used Redux and also Redux Saga for some async api calls. Intending to make the best user experience possible, I've also used awesome libraries such as React Toastify to handle with error/success messages. Here is a list of technlogies (at least what I remeber) that I used to develop the application:

-  [ReactJS](https://reactjs.org/)
-  [Create React App Configuration Override](https://github.com/sharegate/craco)
-  [Redux](https://redux.js.org/)
-  [Redux-Saga](https://redux-saga.js.org/)
-  [React Router v4](https://github.com/ReactTraining/react-router)
-  [styled-components](https://www.styled-components.com/)
-  [Axios](https://github.com/axios/axios)
-  [History](https://www.npmjs.com/package/history)
-  [Immer](https://github.com/immerjs/immer)
-  [Polished](https://polished.js.org/)
-  [React-Toastify](https://fkhadra.github.io/react-toastify/)
-  [React-Icons](http://react-icons.github.io/react-icons/)
-  [react-perfect-scrollbar](https://github.com/OpusCapita/react-perfect-scrollbar)
-  [Unform](https://github.com/Rocketseat/unform)
-  [Yup](https://www.npmjs.com/package/yup)
-  [date-fns](https://date-fns.org/)  
-  [Reactotron](https://infinite.red/reactotron)

## :information_source: How to use this project
To clone and run this application, you'll need Git, NodeJS, Yarn and Docker. 

You just need to run the following commands:

```bash
# Clone this repository
$ git clone https://github.com/riltonfranzonee/gobarber

# Go into the repository
$ cd gobarber

# Install dependencies
$ yarn

# Run the app
$ yarn start
```

Make sure you have the [**RESTful API**](https://github.com/riltonfranzonee/gobarber-api) up and running.

:speech_balloon: Reach me
----------

[*In case you want to reach me*](https://www.linkedin.com/in/rilton-franzone-b975a7198/)



Thank you for taking a look at my project! Made with ♥
