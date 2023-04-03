# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
Data can be bound with v-bind directly within an element tag, or we can use a ref object paired with v-model to bind the value of an input, for example, to an object that can be accessed later.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
With a multi-page application, entire HTML files must be sent to be rendered on a new page. With a single-page application, the ability to alter only portions of a page and re-use components offers higher speed and a dynamic user experience in the right applications.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted will run the provided functions when a page is 'mounted' or loaded.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
One application of the v-model attribute is to achieve two-way data binding with a form. We can define a variable and set its value to ref({}), then we can target that variable and save various key/value pairs to be accessed later.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
The v:on directive has multiple uses, we can target various events such as click or form submission, then execute the necessary function(s).
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
The v-if and v-show directives can allow us to conditionally render elements to the page.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
Using a key on a v-for element allows us to have a reference back to each object we iterated over. For example, if a button is placed on that object, we can pass through the unique key (usually an id) of that object through to the associated function.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
I have used <slot> elements in modals before in order to render different modal contents depending on what page the modal is being called from.
```