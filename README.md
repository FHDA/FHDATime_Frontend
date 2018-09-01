# FHDATime web app

This is FHDATime frontend application.

## 1. Coding style

### 1. No semicolons

1. <http://blog.izs.me/post/2353458699/an-open-letter-to-javascript-leaders-regarding>
2. <http://inimino.org/~inimino/blog/javascript_semicolons>
3. <https://www.youtube.com/watch?v=gsfbh17Ax9I>

Therefore, not to use the semicolon, which is a _JS Standard Code Style_.

[![JS Standard Coding Style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://standardjs.com/rules.html#semicolons)

> No semicolons.

### more...TBA

## 2. FHDAtime structure

We decide to refer from https://daveceddia.com/react-project-structure/

- ```docs/``` - All our documentation should go here.
- ```public/``` - All static page go here. This should be a static page, since react is a one page application, so we should not change a lot in the directory.
- ```src/api``` - All API relate go here. Make calls to a backend API. Put all that code here. For example, put the area-specific API files under there such as userApi.js, productApi.js, etc.
- ```src/components``` - All your Presentational (aka Dumb) components go here.
- ```src/containers``` - The Container components go here. These are the stateful ones, and the ones that make the API calls. If you’re using Redux, these are the ones that are connected to the store. Notice that CSS and tests are in the same folder as their respective components.
- ```src/images``` - images file go here
- ```src/utils``` - You’ll probably end up with miscellaneous utility functions – error handlers, formatters, etc.. go here.
- ```src/index.js``` - This is where you initialize the app and call ReactDOM.render, so it makes sense to keep this at the top level.

## 3. Why are the entire project writing in English

Since we all come from differnt countries in the Silicon valley bay area in CA US, so we should pritice our English writing skill and English communication skill, so we should and we have to write in English.

Second, according to PEP8 from Python:

> ... coders from non-English speaking countries: please write ... in English, unless you are 120% sure that the code will never be read by people who don't speak your language.

In both of reason, we will writing in English

## 4. Welcome to join our team

The project is going on slow and may not be good enough unless more people join and make pull request if possilbe. Therefore, we are very kindly welcome you join our project. Specailly, if you want to make Foothill-Denaza College better.

## 5. How to develop this project

If you are first time clone and develop, remember do ```npm install``` after you clone this repo.

- ```npm start``` - This will start develop mode of react app
- ```npm test``` - This will run unit test for this project
