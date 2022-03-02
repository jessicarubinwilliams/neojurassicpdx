## _This project is not in a complete or portfolio ready state, and should not be considered representational of professional work._

# _neojurassicpdx_

#### _A queryable RESTful API that shares data about pseudo tropical plants appropriate for growing in the Pacific Northwest - 217 different flora, over 1000 plants and trees.  A React front-end that allows the user to search the APIs data._

#### _By **Jessica R. Williams**_

#### _Table of Contents_

<!-- 1. [Preview](#preview) -->
1. [Technologies Used](#technologies)
2. [Description](#description)
3. [Research & Planning Log](#planning)
4. [Setup/Installation Requirements](#setup)
5. [Known Bugs](#bugs)
6. [License](#license)
7. [Contact Information](#contact)

<!-- ## Preview <a id="preview"></a>

* _Direct your browser to a [live version](https://jessicarubinwilliams.github.io/project/index.html) on GitHub Pages._ -->

## Technologies Used <a id="technologies"></a>

* _Bootstrap 4.5.0_
* _Cloud Firestore_
* _CSS_
* _Express_
* _HTML5_
* _Firebase_
* _JavaScript ES6_
* _Node.js 16.6.1_
* _Node Package Manager 7.20.3_
* _React 17.0.2_
* _React Dom 17.0.2_
* _React Scripts 3.2.0_

## Description <a id="description"></a>

_A queryable API using RESTful principles that shares data about the plants and appropriate places to plant them of the garden of Instagram’s [@neojurassicpdx](https://www.instagram.com/neojurassicpdx/) - a pseudo tropical Pacific Northwest garden with an emphasis on foliage - 217 different flora, over 1000 plants and trees.  A React webpage that displays and allows the user to search the APIs data._

## Research & Planning Log <a id="planning"></a>

_This project is a Capstone for my certificate in Web and Mobile Development from [Epicodus](https://www.epicodus.com/) bootcamp. Below is the required log of my research and planning time._

### Saturday, January 29, 2022
* 6:00-6:30pm Create directory, add initial README.md, create repo and link
* 6:30-6:45pm Update README's technology used & fix typos & broken links
* 6:45-7:40pm Add capstone-proposal.md
* 7:45-8:00pm Research Firebase
* 8:00-8:40pm Research building a RESTful API with Firebase web hosting, Cloud Firestore database, Node.js Runtime Environment, and ExpressJS Framework for Middleware. Noteably, watched excellent video series [Building a RESTful API with Cloud Functions and Firestore](https://youtube.com/playlist?list=PLJetLDY7yKupm5WTx02ylh1I25rJLPvXe). The dependencies are outdated but the concepts are helpful.
* 8:40-9:15pm Research ExpressJS Framework for Node.js to use as Middleware and Node.js Runtime Environment. Noteable videos: [Learn Express Middleware In 14 Minutes](https://youtu.be/lY6icfhap2o), [Express JS - What the Heck is Middleware](https://youtu.be/MIr1oxQ3pao), [Express.js Fundamentals - 6 - Middleware Explained](https://youtu.be/9HOem0amlyg)
* 9:15-10pm Design plant database

## Saturday, February 12, 2022
* 1:30-2:00pm Further research building a RESTFUL API with Firebase web hosting, Cloud Firestore database and TypeScript. Watch first half of video [Build a Serverless API with Firebase cloud functions, TypeScript and Firestore](https://www.youtube.com/watch?v=T8SZv6h2WbY). The dependencies are closer to current Firebase 9 but will still require some tweaking.
* 2:00-2:30pm Further research building a RESTFUL API with Firebase web hosting, Cloud Firestore database and TypeScript. Watch second half of video [Build a Serverless API with Firebase cloud functions, TypeScript and Firestore](https://www.youtube.com/watch?v=T8SZv6h2WbY)
* 2:30-3:00pm Research TypeScript. Watch first ~third of video [React & TypeScript - Course for Beginners](https://www.youtube.com/watch?v=FJDVKeh7RJI)
* 3:00-3:30pm Research TypeScript. Watch second ~third of video [React & TypeScript - Course for Beginners](https://www.youtube.com/watch?v=FJDVKeh7RJI)
* 3:30-4:15pm Research TypeScript. Watch final ~third of video [React & TypeScript - Course for Beginners](https://www.youtube.com/watch?v=FJDVKeh7RJI)
* 4:15-4:45pm Research TDD with React. Watch video [Introduction to Test Driven Development with React](https://www.youtube.com/watch?v=7WY1cfRoUJk)
* 4:45-5:30pm Research TDD with React. Watch video [React TDD in 30 Minute - Test Driven Development with Jest and Enzyme](https://www.youtube.com/watch?v=-bmdf1oATQo) and skim article [Test-Driven Development with React, Jest, and Enzyme - Part 1](https://testdriven.io/blog/tdd-with-react-jest-and-enzyme-part-one/)

# Monday, February 28, 2022

* 8pm-9pm Begin building sample API using Firestore, Firebase, Node.js, Express middleware, and Typescript - [See commit history of the sample API's repo](https://github.com/jessicarubinwilliams/ebenezer-don-practice-api/commits/main) - set up project, created and tested in Postman basic helloWorld function to test API set up and link to firebase & firestore

# Tuesday, March 1, 2022

* 10am-11am Continue working on building sample API sample API using Firestore, Firebase, Node.js, Express middleware, and Typescript - [See commit history of the sample API's repo](https://github.com/jessicarubinwilliams/ebenezer-don-practice-api/commits/main) - researched and experimented with how to configure Firebase Functions using .env as well as ES6 import statements. Eventually used require statement because it worked and that's what the Firebase documentation shows. Cobbled together something that works using multiple resources. [Firebase Admin SDK Docs](https://firebase.google.com/docs/admin/setup), [Firebase Environment Configuratin Docs](https://firebase.google.com/docs/functions/config-env), & ["Configuring Firebase Admin SDK with Express"](https://medium.com/@tanya/configuring-firebase-admin-sdk-with-express-931b02ee2f91) Medium article.
* 1:30pm-2:30pm Continue working on building sample API sample API using Firestore, Firebase, Node.js, Express middleware, and Typescript - [See commit history of the sample API's repo](https://github.com/jessicarubinwilliams/ebenezer-don-practice-api/commits/main) - Added post route & tested in Postman
* 2:30pm-3:30pm Continue working on building sample API sample API using Firestore, Firebase, Node.js, Express middleware, and Typescript - [See commit history of the sample API's repo](https://github.com/jessicarubinwilliams/ebenezer-don-practice-api/commits/main) - Worked on getAll route, currently broken & added stretch goals to the README
* 6pm-6:30pm Housekeeping - updated this neglected log

TOTAL DOCUMENTED HOURS TO DATE: 12.5

## Setup/Installation Requirements <a id="setup"></a>

* _Open the terminal on your local machine_
* _If [Node.js](https://nodejs.org/en/) and [Nope Package Manager (npm)](https://www.npmjs.com/) are not installed on your local device, follow the instructions [here](https://www.learnhowtoprogram.com/intermediate-javascript/getting-started-with-javascript/installing-node-js)_
* _Navigate to the directory inside of which you wish to house this project_
* _Clone this project with the following git command `$ git clone <https://github.com/jessicarubinwilliams/neojurassicpdx>`_
* _Navigate to the top level of the repository with the command `$ cd project`_
* _Recreate project environment and install required dependencies with terminal command `$ npm install`_
* _Create production environment with terminal command `$ npm run build`_
* _Open project in a development server in the browser of your choice with the command `$ npm run start`_

## Known Bugs <a id="bugs"></a>
* _Any known issues_
* _should go here_

## License <a id="license"></a>
*[MIT](https://choosealicense.com/licenses/mit/)*

Copyright (c) **_2022 Jessica R. Williams_**

## Contact Information <a id="contact"></a>
**_Jessica R. Williams [mailto](mailto:jessicarubinwilliams@gmail.com)_**