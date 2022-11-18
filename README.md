# PWA Application: J A T E 

## Description
JATE is 'Just Another Text Editor' that runs in the browser. The app is a single-page application that meets the PWA criteria that features a number of data persistence techniques that serve as redundancies in case one of the options is not supported by the browser. The application also functions offline.

## Table of Contents
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Link](#link)
- [Contribution](#contribution)
- [License](#license)

## User Story 
AS A developer <br>
I WANT to create notes or code snippets with or without an internet connection <br>
SO THAT I can reliably retrieve them for later use <br>

## Acceptance Criteria 
GIVEN a text editor web application <br>
WHEN I open my application in my editor <br>
THEN I should see a client-server folder structure <br>
WHEN I run `npm start` from the root directory <br>
THEN I find that my application should start up the back end and serve the client <br>
WHEN I run the text editor application from my terminal <br>
THEN I find that my JavaScript files have been bundled using webpack <br>
WHEN I run my webpack plugins <br>
THEN I find that I have a generated HTML file, service worker, and a manifest file <br>
WHEN I use next-gen JavaScript in my application <br>
THEN I find that the text editor still functions in the browser without errors <br>
WHEN I open the text editor <br>
THEN I find that IndexedDB has immediately created a database storage <br>
WHEN I enter content and subsequently click off of the DOM window <br>
THEN I find that the content in the text editor has been saved with IndexedDB <br>
WHEN I reopen the text editor after closing it <br>
THEN I find that the content in the text editor has been retrieved from our IndexedDB database <br>
WHEN I click on the Install button <br>
THEN I download my web application as an icon on my desktop <br>
WHEN I load my web application <br>
THEN I should have a registered service worker using Workbox <br>
WHEN I register a service worker <br>
THEN I should have my static assets precached upon loading along with subsequent pages and static assets <br>
WHEN I deploy to Heroku <br>
THEN I should have proper build scripts for a webpack application <br>

## Link
https://lit-ravine-86208.herokuapp.com/

## Contribution
Zuleika Tesei (https://github.com/zuetesei) <br>
With the help of TA Dom Stephek! 

## License
This project was created by Zuleika Tesei as part of the curriculum for the UC Davis Coding Boot Camp and Trilogy Education Services.

© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
