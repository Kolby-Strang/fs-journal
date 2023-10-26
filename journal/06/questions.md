# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > main.js

02. What is the difference between a vue `component` and `page`?

  > Functionally nothing, but we call them in different manners to structure our websites in a readable manner

03. What is ***Component-Based Architecture***?

  > Components allow for reusable portions of html-js-css to be implemented easily and quickly 

04. What are the three tags that make up a Vue component?

  > template script style

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > methods that are called at certain periods in the lifecycle of a component, for example, onMounted

06. Which component in Vue does the vue-router use to mount pages onto?

  > the router-view

07. What is the difference between the `AppState` and the state object within a component?

  > the appState carries data that the entire program needs access to while the state is scoped to the template it is on

08. What is the responsibility of `Services` in our Vue projects?

  > to gather and push data from and to our appState and api's

09. What are ***props*** and how are they used? Provide an example

  > props are passed parameters from parent to child components, they are used to make child components reusable through a large variety of applications, usage : <ComponentName :propValue:'PassedValue' />

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > watchEffect(()=>{}) any variable that is read within this lower order function will be watched and on the change of any of those variables the function passed to watchEffect will fire
