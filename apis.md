> api design best practices

rest stands for representational state transfer

apis are commonly structred around a resource, like a large database of information

a resource has an URI identifier, ex: [https://mail.google.com/mail/u/0/?tab=rm#inbox/FMfcdzGlgzjvQfsnQQFGSnfMtHjkw33ert](https://mail.google.com/mail/u/0/?tab=rm#inbox/FMfcdzGlgzjvQfsnQQFGSnfMtHjkw33ert)

the most commonly used HTTP verbs are GET, POST, PUT, DELETE, and PATCH however PATCH doesnt get much shine as it isnt used nearly as much as the others but is still considered pretty common

a uri should be based on or around a collection, ex: [https://dar.io/contact](https://dar.io/contact)

a chatty api means that it requires a lot of requests for a small database. rather than grouping things together needed for a larger response, it picks apart the data one request at a time instead of all at once. 

get returns 200 for success

get returns 404 for not found

post returns 201 for success

delete retruns 204 for success

^Dario Vitorte$