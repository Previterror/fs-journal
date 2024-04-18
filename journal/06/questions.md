# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > The first file loaded in an app

02. What is the difference between a vue `component` and `page`?

  > A component is a section of a page, an individual element that has some function. A page contains many elements some of which may be components.

03. What is ***Component-Based Architecture***?

  > Component Based Architecture enscapsulates responsibility vertically rather than horizontally for any component in a view. A single component will handle its own rendering and api calls but not be able to affect the rest of the page.

04. What are the three tags that make up a Vue component?

  > Script, template, style

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > Lifecycle hooks are instructions on when to execute some action, for example onMounted.

06. Which component in Vue does the vue-router use to mount pages onto?

  > RouterLink

07. What is the difference between the `AppState` and the state object within a component?

  > The appstate is global data available to every part of the app, but the state object is scoped within the component it is in and is not accessible elsewhere.

08. What is the responsibility of `Services` in our Vue projects?

  > To handle the appstate and calls to APIs

09. What are ***props*** and how are they used? Provide an example

  > props are a type of variable we use between components, for example we might pass in a prop of our data model to let a component treat the data it's handling very similarly.

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > computed(()=> AppState)
