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

### Saturday, January 29, 2022 - 4 hours
* 6:00-6:30pm Create directory, add initial README.md, create repo and link
* 6:30-6:45pm Update README's technology used & fix typos & broken links
* 6:45-7:40pm Add capstone-proposal.md
* 7:45-8:00pm Research Firebase
* 8:00-8:40pm Research building a RESTful API with Firebase web hosting, Cloud Firestore database, Node.js Runtime Environment, and ExpressJS Framework for Middleware. Noteably, watched excellent video series [Building a RESTful API with Cloud Functions and Firestore](https://youtube.com/playlist?list=PLJetLDY7yKupm5WTx02ylh1I25rJLPvXe) - by Soren Spangsberg Jorgensen. The dependencies are outdated but the concepts are helpful.
* 8:40-9:15pm Research ExpressJS Framework for Node.js to use as Middleware and Node.js Runtime Environment. Noteable videos: [Learn Express Middleware In 14 Minutes](https://youtu.be/lY6icfhap2o), [Express JS - What the Heck is Middleware](https://youtu.be/MIr1oxQ3pao), [Express.js Fundamentals - 6 - Middleware Explained](https://youtu.be/9HOem0amlyg)
* 9:15-10pm Design plant database

## Saturday, February 12, 2022 - 4 hours (8 total)
* 1:30-2:00pm Further research building a RESTFUL API with Firebase web hosting, Cloud Firestore database and TypeScript. Watch first half of video [Build a Serverless API with Firebase cloud functions, TypeScript and Firestore](https://www.youtube.com/watch?v=T8SZv6h2WbY) - by Ebenezer Don. The dependencies are closer to current Firebase 9 but will still require some tweaking.
* 2:00-2:30pm Further research building a RESTFUL API with Firebase web hosting, Cloud Firestore database and TypeScript. Watch second half of video [Build a Serverless API with Firebase cloud functions, TypeScript and Firestore](https://www.youtube.com/watch?v=T8SZv6h2WbY)  - by Ebenezer Don
* 2:30-3:00pm Research TypeScript. Watch first ~third of video [React & TypeScript - Course for Beginners](https://www.youtube.com/watch?v=FJDVKeh7RJI)
* 3:00-3:30pm Research TypeScript. Watch second ~third of video [React & TypeScript - Course for Beginners](https://www.youtube.com/watch?v=FJDVKeh7RJI)
* 3:30-4:15pm Research TypeScript. Watch final ~third of video [React & TypeScript - Course for Beginners](https://www.youtube.com/watch?v=FJDVKeh7RJI)
* 4:15-4:45pm Research TDD with React. Watch video [Introduction to Test Driven Development with React](https://www.youtube.com/watch?v=7WY1cfRoUJk)
* 4:45-5:30pm Research TDD with React. Watch video [React TDD in 30 Minute - Test Driven Development with Jest and Enzyme](https://www.youtube.com/watch?v=-bmdf1oATQo) and skim article [Test-Driven Development with React, Jest, and Enzyme - Part 1](https://testdriven.io/blog/tdd-with-react-jest-and-enzyme-part-one/)

# Monday, February 28, 2022 - 1 hour (9 total)

* 8pm-9pm Begin building sample API using Firestore, Firebase, Node.js, Express middleware, and Typescript - [See commit history of the sample API's repo](https://github.com/jessicarubinwilliams/ebenezer-don-practice-api/commits/main) - set up project, created and tested in Postman basic helloWorld function to test API set up and link to firebase & firestore

# Tuesday, March 1, 2022 - 6 hours (15 total)

* 10am-11am Continue working on building sample API sample API using Firestore, Firebase, Node.js, Express middleware, and Typescript - [See commit history of the sample API's repo](https://github.com/jessicarubinwilliams/ebenezer-don-practice-api/commits/main) - research and experiment with how to configure Firebase Functions using .env as well as ES6 import statements. Eventually used require statement because it worked and that's what the Firebase documentation shows. Cobbled together something that works using multiple resources. [Firebase Admin SDK Docs](https://firebase.google.com/docs/admin/setup), [Firebase Environment Configuratin Docs](https://firebase.google.com/docs/functions/config-env), & ["Configuring Firebase Admin SDK with Express"](https://medium.com/@tanya/configuring-firebase-admin-sdk-with-express-931b02ee2f91) Medium article.
* 1:30pm-2:30pm Continue working on building sample API sample API using Firestore, Firebase, Node.js, Express middleware, and Typescript - [See commit history of the sample API's repo](https://github.com/jessicarubinwilliams/ebenezer-don-practice-api/commits/main) - Add & deploy post route & test in Postman
* 2:30pm-3:30pm Continue working on building sample API sample API using Firestore, Firebase, Node.js, Express middleware, and Typescript - [See commit history of the sample API's repo](https://github.com/jessicarubinwilliams/ebenezer-don-practice-api/commits/main) - Work on getAll route, currently broken & added stretch goals to the README
* 6pm-6:30pm Housekeeping - updated this neglected log
* 6:30pm-7pm Continue working on building sample API sample API using Firestore, Firebase, Node.js, Express middleware, and Typescript - [See commit history of the sample API's repo](https://github.com/jessicarubinwilliams/ebenezer-don-practice-api/commits/main) - Add & deploy getAll route & test in Postman
* 7pm-7:30pm Continue working on building sample API sample API using Firestore, Firebase, Node.js, Express middleware, and Typescript - [See commit history of the sample API's repo](https://github.com/jessicarubinwilliams/ebenezer-don-practice-api/commits/main) - Add & deploy update & delete routes & test in Postman
* 7:30pm-8pm Continue working on building sample API sample API using Firestore, Firebase, Node.js, Express middleware, and Typescript - [See commit history of the sample API's repo](https://github.com/jessicarubinwilliams/ebenezer-don-practice-api/commits/main) - Add & deploy 400 error handling - user error
* 8pm-8:30pm Research user authentication with Firebase 9. Most helpful resource I found: [Handling user authentication with Firebase](https://blog.logrocket.com/user-authentication-firebase-react-apps/)
* 8:30pm-9pm Create and link [new repo](https://github.com/jessicarubinwilliams/firebase-practice-api-2) & Firebase project for a second practice API. Needing to deploy feature branches to Firestore makes feature branch development less helpful than a new repo at this point.

# Wednesday, March 2, 2022 - 7.75 hours (22.5 total)

* 11:00am-11:30am Research Node.js - highlight was YouTube video [What is Node.js Exactly? - a beginners introduction to Nodejs](https://youtu.be/pU9Q6oiQNd0)
* 12:45pm-1:15pm Research Node.js - start YouTube Node.js tutorial [Node.js Tutorial for Beginners: Learn Node in 1 Hour](https://youtu.be/TlB_eWDSMt4)
* 1:15pm-1:45pm Continue researching Node.js - continue watching YouTube Node.js tutorial [Node.js Tutorial for Beginners: Learn Node in 1 Hour](https://youtu.be/TlB_eWDSMt4)
* 1:45pm-2:15pm Continue researching Node.js - continue watching YouTube Node.js tutorial [Node.js Tutorial for Beginners: Learn Node in 1 Hour](https://youtu.be/TlB_eWDSMt4)
* 2:15pm-2:45pm Continue researching Node.js - continue watching YouTube Node.js tutorial [Node.js Tutorial for Beginners: Learn Node in 1 Hour](https://youtu.be/TlB_eWDSMt4). While technically this is a 1 hour and 20 minute video, I needed to pause and replay a lot both to follow along with the coding as well as to do some side research.
* 2:45pm-3:15pm Continue researching Node.js - finish watching YouTube Node.js tutorial [Node.js Tutorial for Beginners: Learn Node in 1 Hour](https://youtu.be/TlB_eWDSMt4). While technically this is a 1 hour and 20 minute video, I needed to pause and replay a lot both to follow along with the coding as well as to do some side research.
* 3:15pm-3:45pm Research the HTTP Transaction - watch YouTube Node.js tutorial [HTTP Transaction explain with real time example | Working of HTTP](https://youtu.be/Nj8pGsBvcmo) & skim Node.js documentation, [Anatomy of an HTTP Transaction](https://nodejs.org/en/docs/guides/anatomy-of-an-http-transaction/).
* 3:45pm-4:15pm Research Express.js routing - read Express.js documentation: [Express basic routing](https://expressjs.com/en/starter/basic-routing.html), [Express routing](https://expressjs.com/en/guide/routing.html) & [app.METHOD](https://expressjs.com/en/4x/api.html#app.METHOD).
* 5:00pm-5:30pm Research REST APIs with Node.js & Express.js  - begin watching YouTube tutorial [How to build a REST API with Node js & Express](https://youtu.be/pKd0Rpw7O48) - by Programming with Mosh.
* 5:30pm-6:00pm Continue researching REST APIs with Node.js & Express.js  - continue watching YouTube tutorial [How to build a REST API with Node js & Express](https://youtu.be/pKd0Rpw7O48)- by Programming with Mosh.
* 6:00pm-6:30pm Deploy and test in Postman [Practice API 2](https://github.com/jessicarubinwilliams/firebase-practice-api-2) created last night
* 6:30pm-7:00pm Continue researching REST APIs with Node.js & Express.js  - continue watching YouTube tutorial [How to build a REST API with Node js & Express](https://youtu.be/pKd0Rpw7O48)- by Programming with Mosh.
* 7:00pm-7:30pm Continue researching REST APIs with Node.js & Express.js  - finish watching YouTube tutorial [How to build a REST API with Node js & Express](https://youtu.be/pKd0Rpw7O48)- by Programming with Mosh. A few minor updates to [Practice API 2](https://github.com/jessicarubinwilliams/firebase-practice-api-2)
* 7:30pm-8:00pm Continue researching Firebase REST APIs with Node.js & Express.js  - start watching YouTube tutorial [Firebase Node REST API | Firestore | Babel | REST | API](https://youtu.be/DO-PROnaVwo) - by Mahesh Kariya.
* 8:00pm-8:30pm Continue researching Firebase REST APIs with Node.js & Express.js  - finish watching YouTube tutorial [Firebase Node REST API | Firestore | Babel | REST | API](https://youtu.be/DO-PROnaVwo) - by Mahesh Kariya.
* 8:00pm-8:30pm Continue researching Firebase REST APIs with Node.js & Express.js  - finish watching YouTube tutorial [Firebase Node REST API | Firestore | Babel | REST | API](https://youtu.be/DO-PROnaVwo) - by Mahesh Kariya.

# Thursday, March 3, 2022 - 0.5 hours (23 total)
* 7:30pm-8:00 Continue researching Firebase REST APIs with Node.js & Express.js  - type up & organize notes I previoulsy took on YouTube tutorial [Firebase Node REST API | Firestore | Babel | REST | API](https://youtu.be/DO-PROnaVwo) - by Mahesh Kariya. See commit history of [Practice API 2](https://github.com/jessicarubinwilliams/firebase-practice-api-2/commits/main)

# Sunday, March 6, 2022
* 9:30am-10am Continue researching Firebase/Firestore Rest APIs with Node.js & Express.js - rewatch YouTube tutorial [Building a RESTful API with Cloud Functions and Firestore](https://youtu.be/XY5WCkgVfPk) and look for ways to improve [Practice API 2](https://github.com/jessicarubinwilliams/firebase-practice-api-2). See that repo's [commit history](https://github.com/jessicarubinwilliams/firebase-practice-api-2/commits/main).
* 10am-10:30am Research Firebase Local Emulator Suite - used for building, testing & QA without touching production data. Key resource was Firebse Docs [Introduction to Firebase Local Emulator Suite](https://firebase.google.com/docs/emulator-suite#:~:text=The%20Firebase%20Local%20Emulator%20Suite,get%20running%20and%20prototyping%20quickly.)
* 10:30am-11am Continue researching Firebase Local Emulator Suite - used for building, testing & QA without touching production data. Key resources: YouTube Tutorials from Firebse [The Local Firebase Emulator UI in 15 minutes](https://youtu.be/pkgvFNPdiEs) & [How to set up Continuous Integration using the Firebase Emulator Suite](https://youtu.be/VgQwlMtxbAw).pm
* 11am-11:30am Begin rewatching primary tutorial used for Practice API2 and take better notes. [Build a Serverless API with Firebase cloud functions, TypeScript and Firestore](https://www.youtube.com/watch?v=T8SZv6h2WbY) - by Ebenezer Don. See See that repo's [commit history](https://github.com/jessicarubinwilliams/firebase-practice-api-2/commits/main).
* 12pm-12:30pm Continue rewatching primary tutorial used for Practice API2 and take better notes. [Build a Serverless API with Firebase cloud functions, TypeScript and Firestore](https://www.youtube.com/watch?v=T8SZv6h2WbY) - by Ebenezer Don. See See that repo's [commit history](https://github.com/jessicarubinwilliams/firebase-practice-api-2/commits/main).


TOTAL DOCUMENTED HOURS AS OF 3/6 12:30am: 25.5

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