# MVC

* All controllers extend the BaseController.

* Put and Post are the only CRUD methods that usually have a body

* Deletes, Puts, and any Gets that are looking for a specific group will need to take in an ID or some other identifying parameter to specify the request.