# nodejs-test
Proof of concept API with node+express+mongodb

I have made this small API with node.js, express.js and mongoose with a MongoDB database following this YouTube tutorial https://www.youtube.com/watch?v=qwfE7fSVaZM&t=11750s.

It consists of a simple CRUD with two models User and Job, where Job is related with User's ID for the CreatedBy field.

The Api has an authantication system using JWT.
