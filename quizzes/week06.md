# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
main.js
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
A component refers to one 'section' of a page, but can be as large or as small as the developer deems necessary. Components come together to form a full page, which is what is displayed to the user as a whole. Each individual component is interactive, but independent from one another.
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
A for-in loop would be used to render a collection of data to the page using a repeating HTML element.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
<template></template>
<script></script>
<style></style>
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
'Liskov Substitution Principle' - States that objects in a superclass should be replaceable by objects of its sub-class without breaking the application. 
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
Vue mounts pages in router.js by taking in a specific path and attaching that to the specified page to be loaded.
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
The state object within a component can only be accessed from within that same component, whereas the AppState has a global scope in the application and can be accessed from any of the components we may be working with.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Similar to MVC, the Services will be responsible for changing/updating our data in the AppState, as well as making calls to databases.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
app.vue
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
The style tag has the ability to change the appearance of the entire app, the 'scoped' keyword limits its affects to only the component it is housed within.
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
Using the reactive keyword where the data is stored (either the state within a component or the AppState) allows us to observe the data and take action on change (usually drawing the update data to the page or changing the style).
```