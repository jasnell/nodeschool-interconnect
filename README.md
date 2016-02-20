# Nodeschool @ InterConnect

## What is nodeschool?

NodeSchool is an open source project run by volunteers with two goals: 

* To create high quality programming curriculum, and 
* To host community learning events.

### Interactive tutorials

The "workshopper" format was first created by [Substack of the Internet][substack] in Summer 2013 when he wrote the [stream-adventure workshopper][streamadventure].

The defining characteristic of the workshopper is the interactvity and automation. Workshoppers are made up of challenges of increasing difficulty. Each challenge starts by explaining a concept, and then presents a list of requirements for solving the challenge. Learners then try and write a computer program that satisfies the criteria.

When they feel confident about their solution they submit it to the workshop for verification. The workshop runs their solution and checks if all requirements were satisfied. If any are wrong or missing the learner gets contextual feedback and they can try again. If their code passes all of the criteria then they pass the challenge and move on to the next challenge.

All of this happens in an automated way. Workshoppers can be thought of almost like a unit test suite that the learner must make pass by implementing the correct code.

(Copy taken from http://nodeschool.io/about.html)

## Getting Started

### Download and Install Node.js

Head on over to [the download page on Nodejs.org][download].
Grab the installer for the operating system you are on.
Double Click!

#### Choosing the Right Version

There are multiple versions of Node.js. Node.js v4.3.1 is the current Long Term Support release, while Node.js v5.6.0 is the current "stable" release that includes newer language and platform features.

If you favor long term stability over features, choose v4.3.1. If you prefer the latest features, choose v5.6.0. The NodeSchool workshoppers will work with either version!

### An Alternative

If you are on OSX or Linux you might want to consider using a [version manager like nvm][https://github.com/creationix/nvm]
This makes updating and switching between releases much simpler.

### Natively Compiled Modules

Some modules hosted on npm include code that needs to be natively compiled. You will need to have a compilation tool-chain set up on your system if you would like to take advantage of these modules. There is a workshopper below [Going Native][native] that explains the fundamentals.

The [Node.js project Readme][readme] identifies the built requirements for Node.js. In general, you will need a similar build environment to build Natively Compiled Modules.

#### Requirements for OSX/Linux 

* `gcc` and `g++` 4.8 or newer, or 
* `clang` and `clang++` 3.4 or newer;
* Python 2.6 or 2.7
* GNU Make 3.81 or newer
* libexecinfo (FreeBSD or OpenBSD only)

#### Requirements for Windows 

* Python 2.6 or 2.7
* Visual Studio 2013 for Windows Desktop or 
* Visual Studio Express 2013 for Windows Desktop

## When you install...

When you install Node.js, two binaries will be installed: The Node.js application itself and the npm registry client. The Node.js binary is used to run your applications, while the npm client is used to install third party modules from the Node.js ecosystem.

You will use npm to install the Workshoppers used as part of this lab.

## Selected Workshoppers

Below is a list of modules that will help you learn a variety of things. Every workshopper is a node module that you install. The command to install the workshopper can be found below, including a link to the source-code on github.

Once you run a global install of a workshopper you will be able to type the name of it into the terminal to launch it.

### Learn About Javascript

#### javascripting

Learn the basics of JavaScript. No previous programming experience required.
[npm install -g javascripting][javascripting]

#### scope chains & closures

Learn the details of Scope, Scope Chains, Closures, and Garbage Collection.
[npm install -g scope-chains-closures][scc]

#### functional Javascript

Learn fundamental functional programming features of JavaScript in vanilla ES5.
[npm install -g functional-javascript-workshop][functional]

#### Promise It Won't Hurt

Learn to use promises in JavaScript to handle async operations.

[npm install -g promise-it-wont-hurt][promise]

#### Async You

Learn to use the async package.

[npm install -g async-you][async]

### Learn About Node

#### learn you node

Learn the basics of node: asynchronous i/o, http.
[npm install -g learnyounode][learnyounode]

#### stream adventure

Learn to compose streaming interfaces with .pipe().
[npm install -g stream-adventure][streamadventure]

#### ExpressWorks

Learn the basics of the Express.js framework.

[npm install -g expressworks][ExpressWorks]

#### Going Native

An exploration of Node.js from the underside: native C++ add-ons.
[npm install -g goingnative][native]

### Learn About The Browser

#### Browserify Adventure

Use npm modules and node-style require() in the browser with browserify.
[npm install -g browserify-adventure][browserify]

#### perfschool

Find your way through the web performance optimization maze!
[npm install -g perfschool][perfschool]

[Node.js project readme][https://github.com/nodejs/node#build]
[nodeschool][http://nodeschool.io/]
[substack][http://substack.net/]
[download][https://nodejs.org/en/download/]
[nvm][https://github.com/creationix/nvm]
[javascripting][https://www.github.com/sethvincent/javascripting]
[learnyounode][https://www.github.com/workshopper/learnyounode]
[streamadventure][https://github.com/substack/stream-adventure]
[scc][https://github.com/jesstelford/scope-chains-closures]
[functional][https://github.com/timoxley/functional-javascript-workshop]
[ExpressWorks][https://github.com/azat-co/expressworks]
[promise][https://github.com/stevekane/promise-it-wont-hurt]
[async][https://github.com/bulkan/async-you]
[native][https://github.com/workshopper/goingnative]
[browserify][https://github.com/substack/browserify-adventure]
[perfschool][https://github.com/bevacqua/perfschool]
