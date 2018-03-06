# ui-patterns :exclamation:
a git for new UI Patterns for a project that we are developing in angular1.5.x and slowly converting to angular^2


# Testing :dizzy_face:
- unit testing: we are using mocha for unit testing, look in the ./testing folder for an example.
-- run tests by "npm run test" from the project folder. Make sure to follow naming conventions and the meaning behind folder hierarchy! 
offical documentation: https://mochajs.org/#table-of-contents

~~e2e installation + examples: follow the instructions found here http://www.protractortest.org/#/~~

# Javascript
1. New Controller Setup :muscle:
using es6 classes as controllers and in every new file, follow the instructions found here. https://www.timroes.de/2015/07/29/using-ecmascript-6-es6-with-angularjs-1-x/

2. Typescript :sweet_potato:
changing your file from javascript to typescript
  - 1. change the file type from .js to .ts
  - 2. run the gulp file from the cedsci folder "gulp --tomcat h:\cedsci\apachi-tomcat.x.x.x"
  - 3. fix typescript errors listed in terminal output
  - 4. all future changes should be made only to the .ts file
  - 5. both typescript and generated typescript file should be commited. Note, .js must be regenrated when the .ts file is changed. 
  - https://www.typescriptlang.org/

3. Promises :pray:
  - 1. stop using the Q promise library. Typescript polyfills ES6 promises, so use typescript and use ES6 promise syntax 
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
  
  

# Things to do on the project
1) Complete all api test responses, to help eliminate backend issues that appear as front end issues.
2) Integrate angular2 upgrade 
3) page load appearances, to show UI only when the data to display it is availible resulting in a UI that doesnt appear broken
4) page transition appearances, transition smoothly between pages
5) page load time till, the load time is very significant this should be reduced to improve user experiance
6) make the api run independently of the backend, so we can then use external services, such as browser stack, to run our tests.
