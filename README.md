![Repo Sizegit ][repo-size]
![Language][github-language]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![twitter][twitter-shield]][twitter-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
![MIT License][license-shield]

<br />
<p align="center">

<h3 align="center" id="code-command">Code Command</h3>

<p align="center">
Code Command description.
<br />
<a href="#how-to-download"><strong>Explore the docs »</strong></a>
<br />
<br />
<a href="#example">View Demo</a>
.
<a href="https://github.com/Derimarg/code-command/issues">Report Bug</a>
·
<a href="https://github.com/Derimarg/code-command/issues">Request Feature</a>
</p>
</p>
<br />
<br />

> Link web page: https://dg-code-command.herokuapp.com/

<details open="open">
<summary>Table of Contents</summary>
<ul>
<li><a href="#description">Description</a></li>
<li><a href="#technologies">Technologies</a></li>
<li><a href="#how-to-download">Download</a></li>
<li><a href="#installation">Installation</a></li>
<li><a href="#prerequisites">Prerequisites</a></li>
<li><a href="#usage">Usage</a></li>
<li><a href="#roadmap">Roadmap</a></li>
<li><a href="#contributing">Contributing</a></li>
<li><a href="#questions">Questions</a></li>
<li><a href="#license">License</a></li>
</ul>
</details>

---

## Description

Working on an Coding app.

<br/>

### Example:

<br/>
<br/>

![Demo](./assets/img/code-command-demo.gif)

<br/>
<br/>

## Technologies

- <p><a href="https://nodejs.org/">Node.js</a></p>
- <p><a href="https://www.npmjs.com/">NPM</a></p>
- <p><a href="https://reactjs.org/">React</a></p>
- <p><a href="https://www.npmjs.com/package/graphql">NPM GrapghQL</a></p>
- <p><a href="apollographql.com/docs/react/get-started/">NPM Apollo Clinet</a></p>
- <p><a href="https://www.npmjs.com/package/apollo-server-express">NPM Apollo Server Express</a></p>
- <p><a href="https://www.npmjs.com/package/react-router">NPM React Router</a></p>
- <p><a href="https://www.npmjs.com/package/react-router-dom">NPM React Router DOM</a></p>
- <p><a href="https://www.npmjs.com/package/concurrently">NPM Concurrently</a></p>
- <p><a href="https://www.npmjs.com/package/jsonwebtoken">NPM JSON Web Tokens</a></p>
- <p><a href="https://www.npmjs.com/package/jwt-decode">NPM JWT Decode</a></p>
- <p><a href="https://www.npmjs.com/package/nodemon">NPM Nodemon</a></p>
- <p><a href="https://www.npmjs.com/package/if-env">NPM If Env</a></p>
- <p><a href="https://redux.js.org/">Redux</a></p>
- <p><a href="https://www.mongodb.com/">MongoDB</a></p>
- <p><a href="https://www.heroku.com/">Heroku</a></p>

[Back To Top](#code-command)

---

## How to Download

- Simply copy the **SSH** to the terminal or Download the **ZIP File**:

## Installation

- Use the follow command at your terminal, **git clone** (Create a working copy at your local repository):

  ```
  git clone git@github.com:Derimarg/code-command.git
  ```

- After cloning the repository, create your own repository, copy the files to your repository and type the following commands in your terminal.

  ```
  git status

  git add -A

  git commit -m "Message to commit."

  git push or git push origin main
  ```

## Prerequisites

Before using this application, you must install dependencies by running the following command in your terminal at the root of the application:

```
npm install
```

[Back To Top](#code-command)

---

## Usage

This is an open source program, feel free to use it, contact me to request features.

```js script
 "scripts": {
    "start": "if-env NODE_ENV=production && npm run start:prod || npm run start:dev",
    "start:prod": "cd server && npm start",
    "start:dev": "concurrently \"cd server && npm run watch\" \"cd client && npm start\"",
    "install": "cd server && npm i && cd ../client && npm i",
    "seed": "cd server && npm run seed",
    "heroku-postbuild": "cd client && npm run build"
  }
```

### `npm run start:dev`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `git push heroku main`

Will deploy app to heroku

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/Derimarg/code-command/issues) for a list of proposed features (and known issues).

[Back To Top](#code-command)

---

<!-- CONTRIBUTORS -->

## Contributing

Contributions are part of this open source project. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/name-of-feature`)
3. Commit your Changes (`git commit -m "Add some feature"`)
4. Push to the Branch (`git push origin feature/name-of-feature`)
5. Open a Pull Request

## Questions

For additional help or questions about collaboration, contact me at: derimargray@gmail.com

- GitHub - [Derimarg](https://github.com/Derimarg/)
- Twitter - [Derimar Gray](https://twitter.com/DerimarGray)
- Linkedin - [Derimar Gray](https://www.linkedin.com/in/derimar-gray-676275132/)
- Project Repository Link: https://github.com/Derimarg/code-command

[Back To Top](#code-command)

---

## License

MIT License

Copyright (c) 2021 Audry Ford, Derimar Gray, Robin Atalla, George Mendoza

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[repo-size]: https://img.shields.io/github/repo-size/Derimarg/code-command?style=for-the-badge
[github-language]: https://img.shields.io/github/languages/top/Derimarg/code-command?color=yellow&style=for-the-badge
[contributors-shield]: https://img.shields.io/github/contributors/Derimarg/code-command.svg?style=for-the-badge
[contributors-url]: https://github.com/Derimarg/code-command/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Derimarg/code-command.svg?color=9cf&style=for-the-badge
[forks-url]: https://github.com/Derimarg/code-command/network/members
[stars-shield]: https://img.shields.io/github/stars/Derimarg/code-command.svg?color=blueviolet&style=for-the-badge
[stars-url]: https://github.com/Derimarg/code-command/stargazers
[issues-shield]: https://img.shields.io/github/issues/Derimarg/code-command.svg?style=for-the-badge
[issues-url]: https://github.com/Derimarg/code-command/issues
[license-shield]: https://img.shields.io/static/v1?label=license&message=MIT&color=yellowgreen.svg&style=for-the-badge
[twitter-shield]: https://img.shields.io/badge/-Twitter-red.svg?&logo=twitter&style=for-the-badge&color=9cf
[twitter-url]: https://twitter.com/DerimarGray
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/derimar-gray-676275132/
