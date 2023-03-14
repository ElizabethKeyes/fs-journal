# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronous code will continue to run even if a request for data was sent out but not yet received. If you send a request for data to an API then console log res.data, your console log will return undefined in a synchronous function because, at the time of the console log, the data had not been returned. If that status was 200, the data is there, it just wasn't there before the console log fired. In an asynchronous function, we could put the 'await' keyword before the data request, then the code afterwards would not run until that request had been completed. In the second example, the console log would actually contain the data (assuming there were no other errors).
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener in the MVC context is generally placed within the Controller. If the listener is observing a variable in the AppState, each time the assignment operator is used in association with that variable, the listener will set into motion the function that was associated with the variable in the initialization of the listener itself.
appState.on('cats', _DrawCats) will call the _DrawCats function when appState.cats changes, specifically through use of the assignment operator. Otherwise an 'emit' will be needed to trigger the listener.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open-Closed Principle - the code is open for extension but closed for modification.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback is a convention in which a function calls to another function. 
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is a guarantee that some information is going to be returned in the future. The status of a promise can either be 'pending', 'resolved', or 'rejected'. To capture an error from a promise, a try/catch syntax should be used, with the catch passing us back the error, optimally as both a console.error and an error that is visible to the user.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
XMLHttpRequest, fetch, axios.get, 
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application programming interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service is the module responsible for making requests and sending data to the API.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation serves a couple purposes. We want our code to be organized and among other relevant code, especially as applications begin to grow in size. Additionally, encapsulation allows us to be very specific with which data and methods/functions we allow the user to see and interact with.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200 - ok
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
500 - internal server error
```