# Room8

## Description

Decision making app for roommates, friends, or whatever. Anonymous, easy and fast.
Web application supports the creation of multiple polls that use the Borda Count method to rank options.

Application has built in Mail Gun API to allow admin to recieve updates

## DEMO

![Demo of Room8 Application](./room8demo.gif)



## Project Setup

0. Fork this repo
1. Clone to your machine

## Getting Started

0. Update the .env file with your correct local information
1. Install dependencies: `npm i`
2. Fix to binaries for sass: `npm rebuild node-sass`
3. Run migrations: `npm run knex migrate:latest`
  - Check the migrations folder to see what gets created in the DB
4. Run the seed: `npm run knex seed:run`
  - Check the seeds file to see what gets seeded in the DB
5. Run the server: `npm run local`
6. Visit `http://localhost:8080/`

## Contributing

0. Add new remote as the master branch ```$ git remote add absolute-master https://github.com/jelocodes/room8```
1. Pull from master to get latest stable version before working ```git pull absolute-master```
1. Checkout and switch to a new branch named as the feature you're working on ```get checkout -b pwn-noobs```
2. Do local tests
4. Push to your forked copy's branch on Github (not absolute-master) ```git push origin pwn-noobs```
5. Open pull request 
6. Wait for merge

## Dependencies

- Node 5.10.x or above
- NPM 3.8.x or above
