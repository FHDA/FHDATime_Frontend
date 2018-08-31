# fhdatime structure

I decide to refer from https://daveceddia.com/react-project-structure/

```src/api.js``` - Make calls to a backend API. Put all that code here. For example, put the area-specific API files under there such as userApi.js, productApi.js, etc.

```src/components``` - All your Presentational (aka Dumb) components go here.

```src/containers``` - The Container components go here. These are the stateful ones, and the ones that make the API calls. If you’re using Redux, these are the ones that are connected to the store. Notice that CSS and tests are in the same folder as their respective components.

```src/images``` - images file go here

```src/utils``` - You’ll probably end up with miscellaneous utility functions – error handlers, formatters, etc.. go here

```src/index.js``` - This is where you initialize the app and call ReactDOM.render, so it makes sense to keep this at the top level.