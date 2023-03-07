# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```

```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
let property = staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```

```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility Principle
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class contains a constructor which can be used as a 'blueprint' for an object. An instance of a class will use that blueprint to assemble the actual object. Changes can be made to instances of a class without ever changing the class itself.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```

```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The MVC pattern has a couple key purposes. First, it gives developers a great way to organize and divide up code into more manageable file sizes in order to aid in organization and troubleshooting, among other things. Additionally, the MVC pattern restricts the user from accessing certain parts of the program by nesting documents within each other and only actually referencing one from the HTML.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller collects user input and sends that data to the Service. Additionally, the Controller is listening to the AppState.js for any changes (likely from the Service), then drawing those changes to the View accordingly.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The Service does the data processing and manipulation, then passes its information through to AppState.js to be read by the Controller.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model is a skeleton or blueprint for the data that will be drawn using the Controller. The Model will usually have a constructor for an object, but not the actual data to be inserted, that is stored in the AppState.
```
