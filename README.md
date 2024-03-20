# Text Editor Progressive Web Application (PWA)


## Table of Contents
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Process](#process)
* [Deployment](#deployment)

## User Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```


## Acceptance Criteria

```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application
```


## Process

This week we were given starter code.

Resources used:
```
Node.js, Render (deployment)
```
npm package dependencies
```
@babel/core: ^7.15.0
@babel/plugin-proposal-object-rest-spread: ^7.20.7
@babel/plugin-transform-runtime: ^7.15.0
@babel/preset-env: ^7.15.0
@babel/runtime: ^7.15.3
babel-loader: ^8.2.2
code-mirror-themes: ^1.0.0
concurrently: ^5.2.0
copy-webpack-plugin: ^12.0.2
css-loader: ^6.2.0
express: ^4.17.1
html-webpack-plugin: ^5.3.2
http-server: ^0.11.1
idb: ^6.1.2
if-env: ^1.0.4
nodemon: ^2.0.4
style-loader: ^3.2.1
webpack: ^5.51.1
webpack-cli: ^4.8.0
webpack-dev-server: ^4.0.0
webpack-pwa-manifest: ^4.3.0
workbox-webpack-plugin: ^6.2.4
```
Before running the script, install any dependencies with `npm install`.

To invoke the application client (development mode) and server, use the command `npm run start` from the project root directory.

To create a webpack build, use the command `npm run build` from the project root directory.


## Deployment
https://text-editor-pwa-1enl.onrender.com/
![text-editor-pwa](https://github.com/dvdhyn/text-editor-pwa/assets/145178667/4f81ebb8-80e1-417b-93a3-954ff4019d97)
