
# Node JS Interview Question
Given the concepts of a user and his/her account balance that are persisted in a central relational DB, design a distributed and highly resilient service that allows an entity to (a) query balances and (b) transfer balance from one account to another. You have to implement user authentication and request validation using middlewares. The entity will be transacting through a REST interface. After the request has completed emit custom event that console log “Success” or “Failure”. Event should be emitted after every request completion using middlewares. 

***You should consider:***
- The DB schema and its implementation (including the code needed to implement the schema)
- Extensibility of the schema for future feature additions
- The design of the API and its inputs and outputs, including edge cases and thoughts about its extensibility
- The actual implementation code showing it in motion
- Cursory thoughts on how to secure the server
- Thoughts about deployment and scaling under load

___You do not need to submit entire PRDs or other such documentation. Do try to submit the actual working, _buildable_ code. Try not to use an ORM layer in the service.
This is a simple engineering exercise to demonstrate your proficiency in simple API design and implementation, and ability to reason and articulate the trade-offs between the design choices you have made.___
