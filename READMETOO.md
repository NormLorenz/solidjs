# Using the tutorial located [here](https://www.youtube.com/watch?v=pFEZLQ6DOf0)

## tasks
- refactor differences between components and functions
- config.json file
- MSAL
- integrate a sass complier
- linter
- pass/emit props by a component
- how to print a portion of the page
- testing with jest
- figure out why we are loading so much stuff on startup
- firebase/firestore
- menu
  - resized menu not working
  - menu drop down not working
- counter using signal
- footer needs work
- build a utility class for creating updating local storage
- build a utility class for creating updating global storage
- tasks page
  - tasks list using global storage
  - clear input box after use - check tutorial by ebinezer
  - refresh issue after adding new task
  - fix site refresh issue when losing tasks
- nav-link active attribute
- should I be using Component type on all classes?
- refactor local storage to theme, mode, tasks
- understand functions with props
- how to pass props from the router
- fix spelling of App.tsx
- new pages
  - shopping cart
  - google chart
  - movies
  - build a contact form with email
  - git hub
- css
  - dark/light themes
  - bootstrap offcanvas
  - compare bootstrap, picocss, w3css and simplecss

A general Component has no implicit children prop. If desired, you can specify one as in Component<{name: String, children: JSX.Element}>.

```bash
# to launch the app
> npm start
```

```bash
# install the router
> npm install @solidjs/router
```

```bash
# install toast
> npm install solid-toast
```

## to refresh the site
edit <code>src/App.tsx</code> and save to reload.

#8:40 minutes into the lecture

########  ON MOUNT SEEMS TO BE RUNNING TWICE
