# [Jekyll Starter Kit](https://github.com/tony-jones/jekyll-starter-kit/releases/latest)

## Overview

Jekyll Starter Kit is a boilerplate with configurable tools for static site development. These tools provide syncronized cross-device testing with a focus on [performance](#performance). This is a good starting point for developers who want to build a Jekyll site with npm-based (npm run-scripts) tooling.

## Inspiration
This project was inspired by Google's Web Starter Kit and achieves most of the same functionality (noted below)

### Features

| Feature                                | Summary                                                                                                                                                                                                                                                     |
|----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Line Critical CSS                       | Inlining critical “above-the-fold” CSS ensures users can begin interacting with the page faster. I used this [Critical](https://github.com/addyosmani/critical) by Addy Osmani 
| CSS Loaded Asynchronously                     | I used [loadCSS](https://github.com/filamentgroup/loadCSS) to asyncronously load all of my CSS and prevent blocking CSS behavior 
| Sass support                           | Compile [Sass](http://sass-lang.com/) into CSS with ease, bringing support for variables, mixins and more. (Add your assets to the `src` directory and run `npm start` to build)                                                                                                      |
| Performance optimization               | We minify and concatenate JavaScript, CSS, HTML and images to be respectful of our users bandwidths. (Run `npm run start` to create an optimised version of your project to `/dist`)                                                                                                |
| Code Linting               | JavaScript code linting is done using [ESLint](http://eslint.org) - a pluggable linter tool for identifying and reporting on patterns in JavaScript. Web Starter Kit uses ESLint with [eslint-config-google](https://github.com/google/eslint-config-google), which tries to follow the Google JavaScript style guide.                                                                                                |
| Built-in HTTP Server                   | A built-in server for previewing your site locally while you develop and iterate                                                                                                                                                                            |
| Live Browser Reloading                 | Reload the browser in real-time anytime an edit is made without the need for an extension. (Run `npm run start` and edit your files)                                                                                                                           |
| Cross-device Synchronization           | Synchronize clicks, scrolls, forms and live-reload across multiple devices as you edit your project. Powered by [BrowserSync](http://browsersync.io). (Run `npm run start` and open up the IP provided on other devices on your network)                       |
| PageSpeed Insights                     | Web performance metrics showing how well your site performs on mobile and desktop (Run `npm run pagespeed`)                                                                                                                                                    |
| Accessibility                          | Runs a web accessibility audit during the build process. Powered by the Chrome Accessibility Tools (Run `npm run accessibility`)

## Quickstart

[Download](https://github.com/tony-jones/jekyll-starter-kit/releases/latest) the kit or clone this repository and run `npm install`. Run `npm run start` to build on what is included in the `src` directory and start the server.

### Prerequisites
Bring up a terminal and type `node --version`.
Node should respond with a version at or above 0.10.x.
If you require Node, go to [nodejs.org](https://nodejs.org) and click on the big green Install button.

Once you have verified that your system can run JSK, check out the [commands](commands.md) available to get started.

## Performance

Jekyll Starter Kit strives to give you a high performance starting point out of the box. By default, your project will have
a 99/100 on PageSpeed insights. You will need to add caching on your server (8 days recommended) to bring it to 100/100.
![Speed](https://cloud.githubusercontent.com/assets/6729106/12889451/f246f650-ce4c-11e5-9508-3d135978a6c9.png)

Check out our Web Page Test [score](http://www.webpagetest.org/result/160208_92_RHF/) for the default template. 
Visit the [Speed Index](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index) for more info on page tests.

## Browser Support

JSK has autoprefixer using the last three versions of the following browsers:

* Chrome (Google Chrome)
* Edge (Microsoft Edge)
* Firefox (Mozilla Firefox)
* Safari (desktop Safari)
* Opera 
* Internet Explorer 9+

Visit the [Browser List](https://github.com/ai/browserslist) for more information

## Troubleshooting

If you find yourself running into issues during installation or running the tools, please open an [issue](https://github.com/tony-jones/jekyll-starter-kit/issues). I would be happy to discuss how they can be solved.

## Contributing

Contributions, questions and comments are all welcome and encouraged. For code contributions to Jekyll Starter Kit, please see the submit a pull request. There is no formal process established currently, so just fork and submit your code!

## License

Apache 2.0  
Copyright 2016 Tony Jones
