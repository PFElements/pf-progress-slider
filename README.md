# pf-elements
A Polymer 2.0 based collection of reusable web components 

[![Join the chat at https://gitter.im/pf-elements/Lobby](https://badges.gitter.im/pf-elements/Lobby.svg)](https://gitter.im/pf-elements/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/PFElements/pf-progress-bar)

## Demo
[Click here for docs & demo](https://www.webcomponents.org/element/PFElements/pf-progress-bar/demo/demo/index.html)

| Element Name | Latest Version (Bower) | Npm version  | Build Status |
|--------------|------------------------|--------------|--------------|
| [pf-progress-bar](https://github.com/PFElements/pf-progress-bar) | [![GitHub version](https://badge.fury.io/gh/PFElements%2Fpf-progress-bar.svg)](https://badge.fury.io/gh/PFElements%2Fpf-progress-bar) | [![npm version](https://badge.fury.io/js/pf-progress-bar.svg)](https://www.npmjs.com/package/pf-progress-bar) |[![Build Status](https://travis-ci.org/PFElements/pf-progress-bar.svg?branch=master)](https://travis-ci.org/PFElements/pf-progress-bar) | | [pf-progress-bar]|

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

---
# A composite component
`<pf-progress-bar></pf-progress-bar>` Use this element to track the progress of the user, this can be made interactive as well and user can go back to a certain step and submit the progress again, progress bar will update the progress status with the right indication(color). 


# Customization and usage

This custom element can be customized in a number of ways

 <pf-progress-bar>

</pf-progress-bar>

### Events
Custom Event                     | Description                       
---------------------------------|----------------------------------------
`event-add`                      | Add event retuns current selected date ('e.detail.date'), fired when user press add event button  
`event-edit`                     | Edit event retuns event ('e.detail.event'),fired when user press edit event button
        
  

### Methods
The following methods are available for crude events operation:

Methods                                 | Description                           
----------------------------------------|--------------------------
`addNewEvent(event)`                       |  Take event object and add as a into firebase 
`updateEvent(key,event)`                |  Take firebase data ref key and updated event object , update the given ref key node                          
`deleteEvent(key)`                      |  Take record ref key and delete that event                    
            

### Styling
The following custom properties and mixins are available for styling:

Custom property                         | Description                             | Default
----------------------------------------|-----------------------------------------|-------------------------
`--pf-calendar-bg-color`                |  Calendar background                    | #4A4A4A
`--pf-calendar-width`                   |  Calendar Width                         | 420px




## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## Learn more

See the list of elements, demos, and documentation by browsing this collection on webcomponents.org:

### Go to [webcomponents.org](https://www.webcomponents.org/collection/pfelements/pf-elements)

---

## Contributing

Comments, questions, suggestions, issues, and pull requests are all welcome.

### Get in touch with the team

Joing us at [![Join the chat at https://gitter.im/pf-elements/Lobby](https://badges.gitter.im/pf-elements/Lobby.svg)](https://gitter.im/pf-elements/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[Twitter](<a href="https://twitter.com/polymerio" class="twitter-follow-button" data-show-count="false">Follow @polymerio</a>)
[Facebook](https://www.facebook.com/polymerjs)
[Google+](https://plus.google.com/116168214823506639166) 
[YouTube](https://www.youtube.com/channel/UCDKqvDyAn_QTBvCPvrZKTkw) 

### Some ways to help:

- **Test the elements and provide feedback**: We would love to hear your feedback on anything related to the elements, like features, API and design. The best way to start is by trying them out. And to get a quick response, either drop a question/comment on the chat or open an issue in GitHub.
- **Report bugs**: File issues for the elements in their respective GitHub projects.
- **Send pull requests**: If you want to contribute code, check out the development instructions below.

We encourage you to read the [contribution instructions by GitHub](https://guides.github.com/activities/contributing-to-open-source/#contributing) also.

## License

MIT License
