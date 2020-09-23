Section 27: Node.js: An Introduction 0 / 20 | 1hr 44min
- [ ] 477. Module Introduction 2min
- [ ] 478. JavaScript is a Hosted Language 2min
- [ ] 479. Installation & Basics 6min
- [ ] 480. Understanding Modules & File Access 5min
  - require
- [ ] 481. Working with Incoming Http Requests 6min
  ```javascript
  - httpCreateServer((request, response) => { // "spins up a server and sends back a response"
    response.write('hello there');
    response.end();
  });

  const port = 3000;
  server.listen(port); // localhost:3000
  ```  
- [ ] 482. Sending Responses (HTML Data) 4min
  - Kinds of data
  ```javascript
  response.setHeader('Content-Type', 'text/html');
  ```
- [ ] 483. Parsing Incoming Data 11min
  - request object
- [ ] 484. Introducing & Installing Express.js 3min
  - More full-featured server library?
  ```javascript
  npm init
  npm install express --save
  ```
- [ ] 485. Express.js: The Basics 7min

  ```javascript
  const express = require('express');
  const app = express(); // "Middleware object"
  
  // next() function
  ```

- [ ] 486. Extracting Data 4min
- [ ] 487. Rendering Server-side HTML with Templates & EJS 7min
  - Static and Dynamic Content
  - EJS Package
- [ ] 488. Enhancing Our Project 4min
- [ ] 489. Adding Basic REST Routes 12min
- [ ] 490. Understanding CORS (Cross Origin Resource Sharing) 5min
  - your-page.com <--> other-site.com // running on different (in-house?) servers
  - Only requests on the same server
  - Sometimes CORS access is okay
  - Extra headers
    - resource.setHeader('Access-Control-Allow-Origin', '*'); // * or other-site domain
    - resource.setHeader('Access-Control-Allow-Methods', 'POST, GET');
    - resource.setHeader('Access-Control-Allow-Headers', 'Content-Type');
- [ ] 491. Sending the Location ID to the Frontend 2min
- [ ] 492. Adding the GET Location Route 7min
- [ ] 493. Introducing MongoDB (Database) 15min
- [ ] 494. NodeJS Error Handling 1min
- [ ] 495. Wrap Up 2min
- [ ] 496. Useful Resources & Links 1min
