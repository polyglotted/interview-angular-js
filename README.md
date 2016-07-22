# interview-angular-js

Simple interview challenge for Angular JS front end engineers

## Challenge

Build a reusable facet directive in Angular JS that can be configured, data passed to it directly or externally (not in scope for this challenge) and can have behavioral interactions.

### Overview 

**What is faceted search?**

Faceted Search is defined broadly at [Wikipedia](http://en.wikipedia.org/wiki/Faceted_search) and it is much better answered at [Stack Overflow](http://stackoverflow.com/questions/5321595/what-is-faceted-search). It is visual representation for a group of filters that can be applied to search results.

Some of the best visual representations that we like for faceted search is from websites like [Momondo](http://momondo.com) or [Kayak](http://www.kayak.com). While there are multiple representations for a facet like combo-boxes, sliders, histograms, we like to pick the simplest option of multiple check-boxes for a given filter. An example for Airline Facet, when searching for flights between two locations from the above two websites are shown below. 

<img src="https://github.com/polyglotted/interview-angular-js/blob/master/kayak.png?raw=true" width="250" valign="top"> <img src="https://github.com/polyglotted/interview-angular-js/blob/master/momondo.png?raw=true" width="250" valign="top">

> In this challenge, you are expected to build an angular directive for a simple facet like above

**What is an angular directive?**

At a high level, directives are markers on a DOM element (such as an attribute, element name, comment or CSS class) that tell AngularJS's HTML compiler ($compile) to attach a specified behavior to that DOM element (e.g. via event listeners), or even to transform the DOM element and its children. Please refer to [Angular documentation](https://docs.angularjs.org/guide/directive) for more information.

**What is application scaffolding?**

Application scaffolding is a quick way for structuring your project and using standard tools and processes to build an output from your source code. We love [Yeoman](http://yeoman.io/learning/) and its generator framework as a good way to scaffold our UI components and applications. 

As a developer, you are more than free to use any other scaffolding framework as long as the broad categorization of concerns like pre processing, linting, unit testing and packaging your code is automated.

### What are you building?

* Use the yeoman generator https://github.com/leftstick/generator-es6-angular or similar scaffolding framework to create a angular directive
* Implement the logic for rendering a simple facet that can be reused between other projects
* Ability to configure different properties of your directive
* Ability to pass data directly to your directive through a JSON file 
* Handle behaviours when users interact with (click or mouse-over) your directive
* Unit tests to confirm the basic usage of your directive

#### What are we looking for

* You are able to code in a clean and concise fashion
* You can learn quickly and adopt things that you have not come across before
* You have creative ideas and while taking inspiration or learning from best practices from others on the internet, you still have great ethics to produce original work of your own
* You impress us beyond belief :)

### How to submit

Please zip your solution and all assets necessary and email to jobs@polyglotted.co. Wish you good luck.

