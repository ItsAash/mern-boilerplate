<h2 align="center">🔥 MERN BOILER PLATE 🔥</h2>

<p align="center">" A well structured and commented boiler plate code for devs "</p>

## 👷‍♂️ Contents of the backend

- Node and Express server
- Simple _User authentication_ mechanism
- Basic _Route protection_ also enabled
- Implemented _JWT_, token based authentication
- Also added _Role Based Authentication_ sample code
- Express _asyncHandler_ wrapping mechanism for handling async errors
- Routes and Middleware details are well _commented_
- Used dotenv for _Environment Variables_(config.env)
- _Mongoose_ for Db connection in config folder(db.js)
- Powerpacked express middlewares(helmet etc..) for preventing basic attacks (XXS, NoSQL injection)

## 👨‍💻 Contents of the frontend

- Built with React and Redux
- Updated **_Redux Hooks_** usage(useSelector and useDispatch)
- Usage of _**redux-thunk**_ for handling the async code
- Added basic _customizable css_ for easy usage
- _Axios_ for api requests
- Removed tests and extra files

## 🛠 Project Setup Instructions

- To install the Client and Server dependencies.

  ```
  npm run setup
  ```

### Development mode scripts

- To run the both end's using concurrently.

  ```
  npm run dev
  ```

- To run the backend in development mode using Nodemon.

  ```
  npm run server
  ```

- To run the frontend in development mode.

  ```
  npm run client
  ```

### Production mode script

- To build the client and run the server

  ```
  npm run prod
  ```
