# Youtube Downloader

This is a repository that has sample code for Moorad his [Medium Article](https://blog.usejournal.com/how-i-made-my-own-youtube-downloader-using-javascript-and-node-js-160b172f6e10)

## Getting Started

- [Install NodeJS](https://nodejs.org/)

1.You need to clone this repository or download the zip version

```git clone https://github.com/JosVermoesen/ytd
```

2.After you clone the repo (or unzip) you will have to navigate to the Server folder

```cd Server
```

3.Then you will have to install all the packages and dependencies

```npm install
```

4.Finally you need to run it

```bash
node index.js
```

5.If you want to use nodemon (nodemon is a package that will auto restart the server when files are changed) you can run **(Optional)**

```bash
npm run dev
```

or

```bash
nodemon index.js
```

## Recent dependancies

```json
"dependencies": {
    "cors": "^2.8.5",
    "express": "^4.17.3",
    "ytdl-core": "^4.10.1"
  },
  "devDependencies": {
    "nodemon": "^2.0.15"
  }
```
