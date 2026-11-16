# proyecto-final-frontend

Front-end (React + Vite) of a final project built in 2023 (first and only commit: June 2023). It is a trips web app with user accounts, where users can publish trips, comment on them and vote.

## Features

- User registration, account activation by code, login and profile editing (JWT-based auth through a React context and `useAuth` hook)
- Trips: list, detail, create, edit and delete
- Comments and votes on each trip
- Client-side routing with React Router v6

## Stack

React 18, Vite 4, React Router, axios, ESLint.

## Important limitations

- This repository contains only the front-end. The API it calls (`http://localhost:3000/api/v1/...`) is not included, so the app does not work standalone.
- Routes use the React Router v5 `Switch`/`component` API with the v6 package, so it would need a migration before running with the pinned dependencies. Kept as-is as a snapshot of 2023 work.

## Run

```bash
npm install
npm run dev
```
