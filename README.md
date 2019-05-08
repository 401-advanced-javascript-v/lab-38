![CF](http://i.imgur.com/7v5ASc8.png) LAB-38
=================================================

##  Hooks API

### Author: Vanessa

### Links and Resources
* [Code sandbox](https://codesandbox.io/s/4lx3jly0r9)


### Assignment
Refactor the provided To Do application using the Hooks API.

Note that the application should be configured to use the deployed API, with the proper "Secret". Create a `.env` file with the following values

```javascript
REACT_APP_API=https://api-js401.herokuapp.com
REACT_APP_SECRET=supersecret
```

#### Login/Auth System
* Convert the `<Login />` and `<Auth />` components from classes to functional components
  * Implement the `useContext()` hook to tap into the Login Context
  * Use the `useState()` hook in the `<Login />` component to manage form state as the user types.

#### To Do Component
Note that this component is protected by the `<Auth />` system, so make sure that this functionality remains intact.

* Convert from class to a function component
* Use the `useReducer()` hook to manage the To Do List items list
* Use the `useState()` hook to manage the form
  
### Setup
#### `.env` requirements
* `npm i` install dependencies

#### Running the app
* open sandbox link

### Components
Auth
Counter
Header
If
Todo


#### UML
![Data flow](./uml.jpg)
