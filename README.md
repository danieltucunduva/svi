May 11, 2021

# SVI Web Technology Stack and Website Re-write Project

## Desired outcomes

**1) Bring the Core Web Vitals score of all our websites and pages to "Good".**  
  <br>
**2) Simplify, increase efficiency, reduce development time, maintenance time and onboarding time for software development projects.**  
  <br>
**3) Allow the marketing department to easily and directly make visual changes to our websites.**  

## Key findings

### Opportunities for improvement in our websites

Modern user experience guidelines are provided by Google's [Core Web Vitals](https://web.dev/vitals/).

<img alt="Core Web Vitals" width="600" src="https://addyosmani.com/assets/images/core-web-vitals-addy.png">

Google is not yet using the scores as an influence factor for page ranking, but [will do so in the near future](https://searchengineland.com/google-postpones-page-experience-update-rollout-347862).

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

[What And Why React.js](https://www.c-sharpcorner.com/article/what-and-why-reactjs/#:~:text=React.js%20is%20an%20open-source%20JavaScript%20library%20that%20is,Jordan%20Walke%2C%20a%20software%20engineer%20working%20for%20Facebook.)  
[React Popularity and When Not to Use React](https://scotch.io/starters/react/react-popularity-and-when-not-to-use-react#toc-when-not-to-use-react)

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

[Why Choose Node JS For Your Next Project?](https://thebroodle.com/web/why-choose-node-js-for-your-next-project/)  
[Why and When to Use Node.js?](https://relevant.software/blog/why-and-when-to-use-node-js/)

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

[Why Webflow Is the Best Web Design Program Right Now](https://blog.prototypr.io/why-webflow-is-the-best-web-design-program-right-now-f128aef8b45)  
[The Ultimate Webflow Review 2021 ??? a Worthy Tool or Yet Another Site Builder?](https://satoristudio.net/webflow-review/)

## Recommendations  

**1) Re-write our websites using React, Node.js and WebFlow following best practices.**    
<br>
**2) Use this technology stack for all other software projects, and gradually migrate legacy systems.**  
