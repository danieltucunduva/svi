May 11, 2021

# SVI Web Technology Stack and Website Re-write Project

## Desired outcomes

* **Bring the Core Web Vitals score of all our websites and pages to "Good".**  
  <br>
* **Simplify, increase efficiency, reduce development time, maintenance time and onboarding time for software development projects.**  
  <br>
* **Allow the marketing department to easily and directly make visual changes to our websites without assistance from
  software developers.**  

## Key findings

### Opportunities for improvement in our websites

Our websites present a major opportunity for improvement on two fronts: user experience and search ranking, and
efficiency of maintenance and future development.

#### User experience and search ranking

On the user experience and search ranking side, the guidelines are provided by
Google's [Core Web Vitals](https://web.dev/vitals/).

<img alt="Core Web Vitals" width="600" src="https://addyosmani.com/assets/images/core-web-vitals-addy.png">

Google is not yet using the scores as an influence factor for page ranking, but plans to do so in the near future (
insert link).

User experience is vital for conversion. For instance, [up to 40% of users abandon a website](https://neilpatel.com/blog/loading-time/) that takes more than 3 seconds to load, and a 1 second delay can result in a 7% reduction in conversions.

Several of our websites and pages are currently at "needs improvement" and "poor" grades.

(insert images here)

### Opportunities for improvement in efficiency for software development projects

Our websites have been constructed as a patchwork of several programming languages and frameworks: Python, Django, PHP,
Bolt, JavaScript, Bootstrap, Vue.js, etc.

As SVI is not a software company, using a uniform and modern technology stack would greatly reduce developer hours for
maintenance work and for any future changes or additions.  
Adhering to a uniform modern stack would also greatly facilitate recruitment, and reduce onboarding time both for new
developers and for developers switching internally from working in one project to another.

### Modern industry standards for technology stack

#### Front end

Regarding the front end, there is only one programming language currently supported by browsers: **JavaScript**.

JavaScript offers many options of frameworks for front end development.

The market leader is [React](https://reactjs.org/).  
React already has the largest market share, and is still trending
toward even greater dominance.

Companies that use React:

* Netflix
* Facebook
* Airbnb
* Instagram
* BBC
* Flipboard
* Cloudflare
* Dropbox
* Reddit
* ...

#### Back end

Regarding the back end, there are several programming languages and frameworks available, including JavaScript, Python,
Ruby, PHP and others, each accompanied by one or more framework options.

For relatively simple applications (as is the case of our websites) and considering the back end in isolation, there is
no strong technical advantage to any one programming language, as long as good implementation practices are followed.
They all can get the job done.

Given that we can pick between languages, it follows that only one choice is optimal: sticking with the same language
that we already use in the front end, **JavaScript**.

Implementing all of our software systems in a uniform language will provide substantial benefits by reducing development
time, facilitating recruitment, and reducing onboarding time externally and internally, as already noted.

JavaScript offers many options of frameworks for back end development, but there is a clear market
leader: [Node.js](https://nodejs.org/en/).

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

#### No-code technologies and content management systems

In addition to traditional front and back ends written by software developers, the latest addition to modern technology stacks are no-code tools, that allow visual changes to be made directly by non-technical contributors.  

This type of tool allows for marketing department members to directly change visual content on websites, for example.

The market leader for no-code solutions is [WebFlow](https://webflow.com/).

Companies that use WebFlow:

* Dell
* Upwork  
* Rakuten
* Zendesk
* Periscope Data
* AngelList Venture
* Freshly
* Lattice
* Petal
* ...

## Recommendations  

* **Re-write our websites using React, Node.js and WebFlow following best practices.**    
  <br>
* **Use this technology stack for all other software projects, and gradually migrate legacy systems.**  
