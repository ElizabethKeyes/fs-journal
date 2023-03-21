# MVC

* All controllers extend the BaseController.

* Put and Post are the only CRUD methods that usually have a body

* Deletes, Puts, and any Gets that are looking for a specific group will need to take in an ID or some other identifying parameter to specify the request.

* MongoDB is a document database (or document-oriented database) that stores data using BSON strings

* mongoose findByIdAndUpdate(id, update object, options) By default the object returned will be the document before the update was applied. [returndocument.'after'] to return the document after updates.

    `const job = await dbContext.Jobs.findByIdAndUpdate(jobId, jobInfo, { returnDocument: 'after' })`
