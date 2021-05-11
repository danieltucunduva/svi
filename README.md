# SVI Website Re-write Project

As part of our effort to increase lead generation and improve the experience of our customers, we identified an
opportunity to bring our websites to the next level. This document details the recommended approach and technical
decisions underpinning the project.

## Current state

Our websites present a major opportunity for improvement on two fronts: user experience and search ranking, and
efficiency of maintenance and future development.

### User experience and search ranking

On the user experience and search ranking side, the guidelines are provided by
Google's [Core Web Vitals](https://web.dev/vitals/).  
Several of our websites and pages are currently at "needs improvement" and "poor" grades.

Google is not yet using the scores as an influence factor for page ranking, but plans to do so in the near future (TODO
link).

<img alt="Core Web Vitals" width="800" src="https://addyosmani.com/assets/images/core-web-vitals-addy.png">

<br>

### Efficiency of maintenance and future development

Our websites have been constructed as a patchwork of several frameworks and programming languages, and includes outdated
technologies. (TODO list them?).

As SVI is not a software company, using a uniform and modern technology stack would greatly reduce developer hours for
maintenance work and for any future changes or additions.  
Adhering to a uniform modern stack would also greatly facilitate recruitment, and reduce onboarding time both for new
developers and for developers switching internally from working in one project to another.

## Our aim

* **Bring the Core Web Vitals score of all our websites and pages to "Good"**
* **Implement our website using a uniform, modern, high performing technology stack**

## Our technical recommendation

### A brief necessary note on web systems

In broad and simple physical terms, a web system is composed of two connected machines: the client's computer, and a
server hosted by a provider at a remote location.

Just as there are two physical machines, there are two corresponding parts for the software system: front and back.

The front end is the interface that a user can see and interact with in the browser.  
The back end is all else: the application logic that is executed on the remote server, and any data that is stored in a
database.

### Technology stack

#### Front end

Regarding the front end, there is only one programming language currently supported by browsers: **JavaScript**

JavaScript offers many options of frameworks for front end development.

The market leader is [React](https://reactjs.org/). React already has the largest market share, and is still trending
toward even greater dominance.

Companies that use React:

* Netflix
* Facebook
* Instagram
* Airbnb
* Cloudflare
* Dropbox
* BBC
* Flipboard
* Imgur
* Postmates
* Reddit
* ...

#### Back end

Regarding the back end, there are several programming languages and frameworks available, including JavaScript, Python,
Ruby on Rails, PHP and others, each accompanied by one or more framework options.

For relatively simple applications (as is the case of our websites) and considering the back end in isolation, there is
no strong technical advantage to any one programming language, as long as good implementation practices are followed.
They all can get the job done.

Given that we can pick between languages, it follows that only one choice is optimal: sticking with the same language
that we already use in the front end, **JavaScript**.

Implementing all of our software systems in a uniform language will provide substantial benefits in reducing development
time, facilitating recruitment, and reducing onboarding time externally and internally, as already noted.

JavaScript offers many options of frameworks for back end development, but there is a clear market
leader: [Node.js](https://nodejs.org/en/)

Companies that use Node.js:

* Netflix
* NASA
* Trello
* PayPal
* LinkedIn
* Uber
* Twitter
* Groupon
* Medium
* ...

