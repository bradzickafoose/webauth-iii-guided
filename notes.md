# JWT Notes

## Practice

Using the documentation here: https://www.npmjs.com/package/jsonwebtoken, modify the restricted middleware so that the list of users can only be accessed if the token is valid. Assume that the client will send the token as the Authorization header.

in a very localized app such as grocery delivery,

in the landing page it asks you for your zipcode (even if you’re not logged in)…. it rememvers your selection even if you close the application.

- we need a storage mechanism on the client.

  - local storage

- how do we send the data to the server? form.

then the server renders only the available groceries based on that particular zipcode.

- session
- token
