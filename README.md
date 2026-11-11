# Backend-mern

An Express and MongoDB backend for a simple user-management CRUD application.

[Repository](https://github.com/MirzaAlbab/Backend-mern)

## Features

- User routes, controller, and Mongoose model
- JSON request handling and CORS
- Example API requests in request.rest

## Technology

`express` ^4.18.2 · `mongoose` ^6.9.0

## Getting started

Install Node.js and make a MongoDB instance available.

```bash
git clone https://github.com/MirzaAlbab/Backend-mern.git
cd Backend-mern
```

```bash
npm install
```

Create `.env` in the project root with the variable read by `index.js`:

```dotenv
db=mongodb://127.0.0.1:27017/mern_users
```

Start the API:

```bash
node index.js
```

The application listens on `http://localhost:5000`. Review `routes/UserRoute.js` and `request.rest` for endpoint usage.

## Development and checks

The `npm test` command is a placeholder and exits with an error. Use `request.rest` to exercise local endpoints; add automated route and validation tests when extending the API.

## Project structure

- `controllers/` — Request handlers
- `models/` — Data models
- `routes/` — HTTP route definitions

## Project notes

Companion frontend: [Front-mern](https://github.com/MirzaAlbab/Front-mern).

## License

No root `LICENSE` file was present in the reviewed repository. Consult the repository owner about reuse; dependencies and third-party assets retain their own terms.
