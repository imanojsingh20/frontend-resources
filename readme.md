## Resources

### Linux Basics
- [Philosophy of Unix Development](https://medium.com/ingeniouslysimple/philosophy-of-unix-development-aa0104322491)

### Directory Structure
- [Video 1](https://youtu.be/42iQKuQodW4?si=nFx41IjknrL1gYxt)
- [Video 2](https://youtu.be/HbgzrKJvDRw?si=2MKpWltbp7DjY9MT)

### Commands
- [Video 1](https://youtu.be/5XgBd6rjuDQ?si=RkWhn97RWysxasgJ)
- [Video 2](https://youtu.be/gd7BXuUQ91w?si=pSCGfCbDoPd4HJ4a)

---

Once done with the resource, DM me the solution of the below problem.

1. How to install a package.
2. How to remove a package.
3. What does `sudo apt purge package_name` do.
4. Ways to write into a file.
5. What does `sudo` do.
6. How to rename a file.

## CLI Assessment

Create the following directory structure. (Create empty files where necessary)

```plaintext
hello
├── five
│   └── six
│       ├── c.txt
│       └── seven
│           └── error.log
└── one
    ├── a.txt
    ├── b.txt
    └── two
        ├── d.txt
        └── three
            ├── e.txt
            └── four
                └── access.log
```

1. **Delete all the files having the `.log` extension**
2. **Add the following content to `a.txt`**:

Unix is a family of multitasking, multiuser computer operating systems that derive from the original AT&T Unix, development starting in the 1970s at the Bell Labs research center by Ken Thompson, Dennis Ritchie, and others


3. **Delete the directory named `five`**
4. **Rename the `one` directory to `uno`**
5. **Move `a.txt` to the `two` directory**

### Submission Instructions

Copy and paste the commands into a GitHub Gist with an explanation for each command. Once done, send the Gist link to me.

Pipes and Redirection

[Video 1](https://www.youtube.com/watch?v=Bzd7XfApxLI) 
[Video 2](https://www.youtube.com/watch?v=VgbnndezHbw)

## CLI Assessment II

### Pipes
- Download the contents of "Harry Potter and the Goblet of fire" using the command line from [here](https://raw.githubusercontent.com/bobdeng/owlreader/master/ERead/assets/books/Harry%20Potter%20and%20the%20Goblet%20of%20Fire.txt)
- Print the first three lines in the book
- Print the last 10 lines in the book
- How many times do the following words occur in the book?
  - Harry
  - Ron
  - Hermione
  - Dumbledore
- Print lines from 100 through 200 in the book
- How many unique words are present in the book?

### Processes, ports
- List your browser's process ids (pid) and parent process ids(ppid)
- Stop the browser application from the command line
- List the top 3 processes by CPU usage.
- List the top 3 processes by memory usage.
- Start a Python HTTP server on port 8000
- Open another tab. Stop the process you started in the previous step
- Start a Python HTTP server on port 90
- Display all active connections and the corresponding TCP / UDP ports.
- Find the pid of the process that is listening on port 5432

### Misc
- What's your local IP address?
- Find the IP address of google.com
- How to check if Internet is working using CLI?
- Where is the node command located? What about code?

### Submission: 

Copy and paste the commands into a github gist with explanation, and send the gist link to me.

## Reverse-i search 

- [LinkedIn - Reverse-i Search](https://www.linkedin.com/pulse/reverse-i-search-bashzsh-terminal-ala-garbaa?utm_source=share&utm_medium=member_ios&utm_campaign=share_via)

## Getting started with Nodejs

Make sure you have installed
- NodeJs - [Download](https://nodejs.org/en/download)
- NPM 
- NVM (node version manager) - [NVM GitHub](https://github.com/nvm-sh/nvm)

Find out
- what is NVM.
- Nvm commands.
- How to check node and npm version.
- What is npm.

## Getting started with JS.

- [Codecademy - Introduction to JavaScript](https://www.codecademy.com/learn/introduction-to-javascript)
- [YouTube - Video 1](https://youtu.be/PkZNo7MFNFg?si=7_aMu7XZ7hFvCIum)
- [YouTube - Video 2](https://youtu.be/hdI2bqOjy3c?si=0Ir4aXNbN0C-j4zL)

Finish any one. And Mandatory read

### Scopes and Closures
- [CSS-Tricks](https://css-tricks.com/javascript-scope-closures/)
- [UI.dev](https://ui.dev/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/)

Very useful in day to day development.


Before starting the assessment, learn git basics.

- [YouTube - Video 1](https://youtu.be/RGOj5yH7evk?si=YgMZXpNvmhMi4SbY)
- [YouTube - Video 2](https://youtu.be/8JJ101D3knE?si=AJV3IoDgcpTUQtM2)

## JS Cars Assessment 

To help us use arrays with real world problems we are going to simulate a used car dealer that has 50 cars in their inventory. The car dealer has all of their inventory housed in the array seen below. Scroll down past the data to find out how you can help the car dealer.

**PROJECT RESTRICTION:** You can't use map, reduce, or filter to solve these problems. Only use native JavaScript for loops. No other types of loops are allowed.

Create a function for each problem in a file called

- problem1.js
- problem2.js
- problem3.js

and so on in the root of the project.

Ensure that the functions in each file is exported and tested in its own file called

- testProblem1.js
- testProblem2.js
- testProblem3.js

and so on in a folder called test.

Each function must take at least one argument. The first argument must always be the inventory.

**Example:**
```javascript
const result = problem1(inventory);
```

If you want to pass more arguments, that is up to you.

Create a new git repo on github for this project, ensure that you commit after you complete each problem in the project. Ensure that the repo is a public repo.

## Problems:

```javascript
let inventory = [{"id":1,"car_make":"Lincoln","car_model":"Navigator","car_year":2009},
{"id":2,"car_make":"Mazda","car_model":"Miata MX-5","car_year":2001},
{"id":3,"car_make":"Land Rover","car_model":"Defender Ice Edition","car_year":2010},
{"id":4,"car_make":"Honda","car_model":"Accord","car_year":1983},
{"id":5,"car_make":"Mitsubishi","car_model":"Galant","car_year":1990},
{"id":6,"car_make":"Audi","car_model":"riolet","car_year":1995},
{"id":7,"car_make":"Smart","car_model":"Fortwo","car_year":2009},
{"id":8,"car_make":"Audi","car_model":"4000CS Quattro","car_year":1987},
{"id":9,"car_make":"Ford","car_model":"Windstar","car_year":1996},
{"id":10,"car_make":"Mercedes-Benz","car_model":"E-Class","car_year":2000},
{"id":11,"car_make":"Infiniti","car_model":"G35","car_year":2004},
{"id":12,"car_make":"Lotus","car_model":"Esprit","car_year":2004},
{"id":13,"car_make":"Chevrolet","car_model":"Cavalier","car_year":1997},
{"id":14,"car_make":"Dodge","car_model":"Ram Van 1500","car_year":1999},
{"id":15,"car_make":"Dodge","car_model":"Intrepid","car_year":2000},
{"id":16,"car_make":"Mitsubishi","car_model":"Montero Sport","car_year":2001},
{"id":17,"car_make":"Buick","car_model":"Skylark","car_year":1987},
{"id":18,"car_make":"Geo","car_model":"Prizm","car_year":1995},
{"id":19,"car_make":"Oldsmobile","car_model":"Bravada","car_year":1994},
{"id":20,"car_make":"Mazda","car_model":"Familia","car_year":1985},
{"id":21,"car_make":"Chevrolet","car_model":"Express 1500","car_year":2003},
{"id":22,"car_make":"Jeep","car_model":"Wrangler","car_year":1997},
{"id":23,"car_make":"Eagle","car_model":"Talon","car_year":1992},
{"id":24,"car_make":"Toyota","car_model":"MR2","car_year":2003},
{"id":25,"car_make":"BMW","car_model":"525","car_year":2005},
{"id":26,"car_make":"Cadillac","car_model":"Escalade","car_year":2005},
{"id":27,"car_make":"Infiniti","car_model":"Q","car_year":2000},
{"id":28,"car_make":"Suzuki","car_model":"Aerio","car_year":2005},
{"id":29,"car_make":"Mercury","car_model":"Topaz","car_year":1993},
{"id":30,"car_make":"BMW","car_model":"6 Series","car_year":2010},
{"id":31,"car_make":"Pontiac","car_model":"GTO","car_year":1964},
{"id":32,"car_make":"Dodge","car_model":"Ram Van 3500","car_year":1999},
{"id":33,"car_make":"Jeep","car_model":"Wrangler","car_year":2011},
{"id":34,"car_make":"Ford","car_model":"Escort","car_year":1991},
{"id":35,"car_make":"Chrysler","car_model":"300M","car_year":2000},
{"id":36,"car_make":"Volvo","car_model":"XC70","car_year":2003},
{"id":37,"car_make":"Oldsmobile","car_model":"LSS","car_year":1997},
{"id":38,"car_make":"Toyota","car_model":"Camry","car_year":1992},
{"id":39,"car_make":"Ford","car_model":"Econoline E250","car_year":1998},
{"id":40,"car_make":"Lotus","car_model":"Evora","car_year":2012},
{"id":41,"car_make":"Ford","car_model":"Mustang","car_year":1965},
{"id":42,"car_make":"GMC","car_model":"Yukon","car_year":1996},
{"id":43,"car_make":"Mercedes-Benz","car_model":"R-Class","car_year":2009},
{"id":44,"car_make":"Audi","car_model":"Q7","car_year":2012},
{"id":45,"car_make":"Audi","car_model":"TT","car_year":2008},
{"id":46,"car_make":"Oldsmobile","car_model":"Ciera","car_year":1995},
{"id":47,"car_make":"Volkswagen","car_model":"Jetta","car_year":2007},
{"id":48,"car_make":"Dodge","car_model":"Magnum","car_year":2008},
{"id":49,"car_make":"Chrysler","car_model":"Sebring","car_year":1996},
{"id":50,"car_make":"Lincoln","car_model":"Town Car","car_year":1999}];
```

```plaintext
// ==== Problem #1 ====
// The dealer can't recall the information for a car with an id of 33 on his lot. Help the dealer find out which car has an id of 33 by calling a function that will return the data for that car. Then log the car's year, make, and model in the console log in the format of:
// "Car 33 is a *car year goes here* *car make goes here* *car model goes here*"

// ==== Problem #2 ====
// The dealer needs the information on the last car in their inventory. Execute a function to find what the make and model of the last car in the inventory is?  Log the make and model into the console in the format of:
// "Last car is a *car make goes here* *car model goes here*"

// ==== Problem #3 ====
// The marketing team wants the car models listed alphabetically on the website. Execute a function to Sort all the car model names into alphabetical order and log the results in the console as it was returned.

// ==== Problem #4 ====
// The accounting team needs all the years from every car on the lot. Execute a function that will return an array from the dealer data containing only the car years and log the result in the console as it was returned.

// ==== Problem #5 ====
// The car lot manager needs to find out how many cars are older than the year 2000. Using the array you just obtained from the previous problem, find out how many cars were made before the year 2000 and return the array of older cars and log its length.

// ==== Problem #6 ====
// A buyer is interested in seeing only BMW and Audi cars within the inventory.  Execute a function and return an array that only contains BMW and Audi cars.  Once you have the BMWAndAudi array, use JSON.stringify() to show the results of the array in the console.
```

## GIT

### GIT with VSCode
- [YouTube](https://youtu.be/i_23KUAEtUM?si=Ptj6rwrJR2lGJwFU)

### GIT Branch
- [YouTube](https://www.youtube.com/watch?v=e2IbNHi4uCI)

**Optional:**
- [Learn Enough Git to Be Dangerous](https://www.learnenough.com/git-tutorial)

**Practice Link**
- [Learn Git Branching](https://learngitbranching.js.org) (at least 3 times)
  - Main:
    - First 4 sections
    - Leave the advanced part
  - Remote:
    - Both sections

### Git Standard Practices
- Using .gitignore
  - [FreeCodeCamp](https://www.freecodecamp.org/news/gitignore-what-is-it-and-how-to-add-to-repo/)
- Good Commit Messages
  - [Chris Beams' Blog](https://chris.beams.io/posts/git-commit/)

**Making Effective Commits on Git**

1. **Small Commits**
   - Make small commits. Break down tasks into micro-tasks and commit for each microtask. This creates a detailed work history and facilitates easier rollback.
2. **Commit Often**
   - Commit after every micro-task. Avoid waiting until the end of the day to commit to prevent loss of work history.
3. **Commit Working Code**
   - Always commit working code. Ensure that committed changes do not break the codebase.
4. **Diff Your Code**
   - Before committing, use your IDE's diff tool to review changes. Avoid committing debug logs, comments, or temporary code.
5. **Always Test Your Code**
   - Thoroughly test changes before committing. Ensure that changes do not break existing features.
6. **Avoid Committing Passwords & Secrets**
   - Never commit sensitive information like API keys, passwords, or secrets to the repository to prevent security breaches.
7. **Undoing Changes**
   - Refer to [Oh Shit, Git!](https://ohshitgit.com/) for instructions on undoing various types of changes such as committing the wrong message, skipping files, committing to the wrong branch, etc.

## NPM

- **NPM Crash Course** - [YouTube](https://www.youtube.com/watch?v=jHDhaSSKmB0)

### Modules
- [Node Module Exports Explained with JavaScript Export Function Examples](https://www.freecodecamp.org/news/node-module-exports-explained-with-javascript-export-function-examples/)
- **Video** - [YouTube](https://www.youtube.com/watch?v=hyYbs3SANRo)

## Higher Order Array Functions
- Watch the videos and then practice
  - [Video 1](https://www.youtube.com/watch?v=zdp0zrpKzIE)
  - [Video 2](https://www.youtube.com/watch?v=rRgD1yVwIvE)

## Closures and Hoisting

**Hoisting:**
- [YouTube](https://youtu.be/Fnlnw8uY6jo?si=oxu33g2y976WP8bU)
- [YouTube](https://youtu.be/EvfRXyKa_GI?si=REByVP7f-_GLQil9)

**Closures:**
- [YouTube](https://youtu.be/3a0I8ICR1Vg?si=Qc7xIFPqAilAKeSb)
- [YouTube](https://youtu.be/qikxEIxsXco?si=RDVpkkDgWZDkhwYL)

## Car Inventory Assessment II

Do the car inventory assessment with

**PROJECT RESTRICTION:** Use map, filter, reduce, Higher order array methods.

**Submission:** share the github repository link.

## Cases
- [Naming Conventions](https://winnercrespo.com/naming-conventions/)

## Convention
- [A Comprehensive Guide to Naming Conventions in JavaScript](https://medium.com/@kjschelling/a-comprehensive-guide-to-naming-conventions-in-javascript-46a7518e4807)

## Best Practices When Starting NodeJS Projects
- [YouTube](https://www.youtube.com/watch?v=X_UQbPnvSx4)

# JS Objects Assessment

- Use the `testObject` provided to test your functions.

**Complete the following underscore functions:**

**Note:** Reference [Underscore.js](http://underscorejs.org/) and [MDN](https://developer.mozilla.org/) for examples.

**Create a function for each problem in a file called:**
- `keys.js`
- `values.js`
- `pairs.js`

**Ensure that the functions in each file are exported and tested in their own file called:**
- `testKeys.js`
- `testValues.js`
- `testPairs.js`

**Create a new git repo on GitLab for this project. Ensure that you commit after you complete each problem in the project. Ensure that the repo is a public repo.**

**When you are done, send the GitLab URL to your mentor.**

```javascript
const testObject = { name: 'Bruce Wayne', age: 36, location: 'Gotham' }; // use this object to test your functions

function keys(obj) {
    // Retrieve all the names of the object's properties.
    // Return the keys as strings in an array.
    // Based on http://underscorejs.org/#keys
}

function values(obj) {
    // Return all of the values of the object's own properties.
    // Ignore functions
    // http://underscorejs.org/#values
}

function mapObject(obj, cb) {
    // Like map for arrays, but for objects. Transform the value of each property in turn by passing it to the callback function.
    // http://underscorejs.org/#mapObject
}

function pairs(obj) {
    // Convert an object into a list of [key, value] pairs.
    // http://underscorejs.org/#pairs
}

/* STRETCH PROBLEMS */

function invert(obj) {
    // Returns a copy of the object where the keys have become the values and the values the keys.
    // Assume that all of the object's values will be unique and string serializable.
    // http://underscorejs.org/#invert
}

function defaults(obj, defaultProps) {
    // Fill in undefined properties that match properties on the `defaultProps` parameter object.
    // Return `obj`.
    // http://underscorejs.org/#defaults
}
```

## Value vs Reference Types

- [YouTube](https://youtu.be/fD0t_DKREbE?si=kFDs1c0WUbFON6ca)

## Asynchronous JS

- Callbacks, Promises, Async Await
  - [YouTube](https://youtu.be/PoRJizFvM7s?si=Apltq8M3yisVLW7B)
  - [FreeCodeCamp](https://www.freecodecamp.org/news/javascript-async-await-tutorial-learn-callbacks-promises-async-await-by-making-icecream/)

**Make sure you cover all these topics:**
- Callback functions
- Callback hell
- Promises
- Promise chaining
- Async await
- Try catch block


# IPL Data Project I

Download the data from:
[https://www.kaggle.com/manasgarg/ipl](https://www.kaggle.com/manasgarg/ipl)

There should be 2 files:
- `deliveries.csv`
- `matches.csv`

In this data assignment, you will transform raw data of IPL to calculate the following stats:

1. Number of matches played per year for all the years in IPL.
2. Number of matches won per team per year in IPL.
3. Extra runs conceded per team in the year 2016.
4. Top 10 economical bowlers in the year 2015.
5. Find the number of times each team won the toss and also won the match.
6. Find a player who has won the highest number of Player of the Match awards for each season.
7. Find the strike rate of a batsman for each season.
8. Find the highest number of times one player has been dismissed by another player.
9. Find the bowler with the best economy in super overs.

Implement the functions, one for each task. Use the results of the functions to dump JSON files in the output folder.

## Instructions:

1. Create a new repo with name js-ipl-data-project on GitHub before starting the implementation of the solution.
2. Make sure to follow proper Git practices.
3. Before submission, ensure that all the points in the below checklist are covered:
   - Git commits
   - Directory structure
   - `package.json` - dependencies, devDependencies
   - `.gitignore` file
   - Proper/Intuitive Variable names
   - Separate module for functions

## Directory structure:

```	
|src
├── server
│   └── 1-matches-per-year.js
│   └── 2-matches-won-per-team-per-year.js
└── public
|   ├── output
|       ├── matchesPerYear.json
|       └── ...
└── data
|   ├── matches.csv
|   ├── deliveries.csv
|package.json
|package-lock.json
|.gitignore
```


## More on Async JS
Learn what below methods do and share usage example in github gist:

- Promise.all
- Promise.race
- Promise.any
- Promise.finally()

Event Loop is very important to understand!!
[Watch Video](https://m.youtube.com/watch?v=8aGhZQkoFbQ)

## HTML/CSS

Those who are done with all the assessment and resources, start with HTML and CSS.

### Complete any 1:
- [Shay Howe's Learn HTML/CSS](https://learn.shayhowe.com/)
- [Marksheet](https://marksheet.io/)

### HTML Crash Course:
- [Watch Video](https://youtu.be/UB1O30fR-EE?si=ZnZGxUIMdCLo8yV_)

### CSS Crash Course:
- [Watch Video](https://youtu.be/yfoY53QXEnI?si=9ih6lkqYMUO1RAuK)

### VSCode setup:
- [Watch Video](https://www.youtube.com/watch?v=aydFCQiUW44)

### Clean code:
- [Watch Video](https://www.youtube.com/watch?v=vPXzVNmCPg4)

### CSS Selectors:
- [How CSS Selectors Work](https://css-tricks.com/how-css-selectors-work/)

### CSS Specificity:
- [Watch Video](https://youtu.be/CHyPGSpIhSs?si=xfBReNGjcqMFgZbl)

### CSS Box Model:
- [Watch Video](https://www.youtube.com/watch?v=rIO5326FgPE)

### Flexbox:
- [CSS Flex Video](https://flexboxfroggy.com/)

### Flexbox games:
- [Flexbox Froggy](https://flexboxfroggy.com/)
- [Flexbox Defense](http://www.flexboxdefense.com/)

### Default Browser Styles:
![Default Browser Styles](/assets/image_from_ios.jpg)

## CSS Layout drills:
- [CSS Layout Drills](https://gitlab.com/mountblue/js/css-layout-drills)

Create a [Codepen](https://codepen.io) collection with solutions for all problems and submit the Codepen collection URL

*NOTE:* Each problem can have multiple solutions. Also, ignore the div numbers, they have been used for illustrations only.

## Pricing Page Project

### Instructions

1. Clone this repository: [Pricing Page Repository](https://gitlab.com/manoj.s4/pricing-html-css/-/blob/master/README.md)
2. Clone it in your local machine
3. Make regular commits to your project
4. Optionally use reset.css

Share the deployed link of the pricing page.

There are many static website hosting available. Like GitHub Pages and Netlify.

## Responsive Design

Those who are done with the pricing page go through these resources:

### Responsive Web Design
- [Watch Video](https://www.youtube.com/watch?v=Wm6CUkswsNw)

### Relative Units
- [The Lengths of CSS](https://css-tricks.com/the-lengths-of-css/)
- [Building Resizeable Components](https://css-tricks.com/building-resizeable-components-relative-css-units/)

### CSS Media Queries
- [CSS Media Queries](https://css-tricks.com/css-media-queries/)
- [Logic in Media Queries](https://css-tricks.com/logic-in-media-queries/)

## Design Daily
Choose any 1 design for this website and work on it.
- [UI Design Daily](https://www.uidesigndaily.com)

Send me the design first by 2pm. Then start on it. Share GitHub link.

Additionally, pick any design daily from the website and develop it until you have some level of confidence in CSS.

**Responsive Drills**
- [Responsive Layout Drills](https://gitlab.com/mountblue/js/responsive-layout-drill)

Create a Codepen collection with solutions and submit the collection URL.

## JS DOM

Those who are done with the responsive assessment, start with JS DOM.

- [Watch Video](https://m.youtube.com/watch?list=PLillGF-RfqbYE6Ik_EuXA2iZFcE082B3s&v=0ik6X4DJKCc)

## Internet Basics
- [Website Terminology](https://www.pagecloud.com/blog/website-terminology)

**Explore more on topics:**
- DNS
- HTTP vs HTTPS
- SEO

**Rendering and How Browsers Work**
- [How Browser Rendering Works](https://blog.logrocket.com/how-browser-rendering-works-behind-scenes/)
- [Watch Video](https://www.youtube.com/watch?v=0IsQqJ7pwhw)

## More on JS DOM

**Chrome Dev Tools**
- [Watch Video](https://www.youtube.com/watch?v=x4q86IjJFag)

**Web Storage APIs**
- [Watch Video](https://www.youtube.com/watch?v=MOd5cTJ6kaA)

**Introduction**
- [Web Platform](https://flaviocopes.com/web-platform/)

**Web Storage**
- [Web Storage API](https://flaviocopes.com/web-storage-api/)
- [Data Storage](https://javascript.info/data-storage)

**Event Lifecycle in JS DOM (Bubbling and Capture)**
- [Understanding DOM Event Life Cycle](https://medium.com/prod-io/javascript-understanding-dom-event-life-cycle-49e1cf62b2ea)

## HTML, CSS, JS Project
- [React Community Examples](https://reactjs.org/community/examples.html)
- [React Practice Projects](https://daveceddia.com/react-practice-projects/)

Pick one project from these links, DM me your choice.

You need to start these projects in HTML, CSS, and JS. Do NOT do these projects in React.

## Memory Game
Do design research for the memory game and send it to me by today EOD.

Project for reference:
- [Memory Game](https://gitlab.com/mountblue/cohort-12-js-1/memory-game)

## Getting Started with React

Those who are done with the existing resources, start with React.

**Prerequisites:**
- JS Library vs Framework
- [Client-side Frameworks](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks)
- [Webpack](https://ui.dev/webpack/)
- [Polyfills](https://ui.dev/compiling-polyfills/)
- [Classes](https://javascript.info/class)
- [Class Inheritance](https://javascript.info/class-inheritance) 
- What is React
- CSR vs SSR

### Babel & Webpack with React

Go through the following articles for a good understanding of the topic. You do not need to implement anything.

- [JavaScript Transpilers](https://scotch.io/tutorials/javascript-transpilers-what-they-are-why-we-need-them)
- [Babel and Webpack's Role in Create React App](https://medium.com/@imrobinkim/babel-and-webpacks-role-in-create-react-app-3a827ad460a2)

### ReactJS

### React Tutorials (Do Any One)**
- [Scrimba](https://scrimba.com/g/glearnreact)
- [Tyler McGinnis](https://tylermcginnis.com)
