# trello-clone-mern

> **Trello Clone** Application using `MERN` stack, `ChakraUI`, and `Docker`

![Trello clone](screenshot.gif)

### [Demo on Vercel](https://trello-clone-one.vercel.app/)

## Features

- Login/Register with `JWT` token authentication
- Ability to **create**/**update**/**delete** the board
- Ability to **add**/**update**/**move**/**delete** the card
- Background image library for the board
- Add labels to the card
- Supports adding of detail description in the card
- Invite user to the board
- Assign a card to the user

## Requirements

```yaml
node.js: v18.17.0
npm: 9.6.7
yarn: 1.22.22
```

## Steps to run this on your local

First [install the `MongoDB Compass`](https://www.mongodb.com/try/download/compass) for better visualization of data with MongoDB server.

1. Clone this repo
2. Create `.env.local` and add this **env** variable `LOCAL_MONGODB=mongodb://localhost:27017/trello`
   Add `JWT_SECRET_KEY=randomstrings`
3. Run `yarn install`
4. Run `yarn dev`

> For unsplash gallery, api key is needed which can be generated from unsplash website

### run the project using docker

Install docker on machine and start it

1. Create `.env.development` file.
2. Add `LOCAL_MONGODB=mongodb://mongodb:27017/trello`
3. Run `docker-compose up`

## Tech stacks

- `Nextjs` with `typescript`
- `MongoDB` for local development
- `Mongo Atlas` for production DB
- `Chakra UI` library

---

&copy; 2021 - 2024 @codeguru827

All rights reserved.
