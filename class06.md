# Reading notes for class 6 reading

>Javascript object
objects group together variables to make a model of something you would recognize from the real world. 
for example:
## the hotel object
`var hotel = {`
`name : 'dario',`
`rooms: 9,`
`booked: 1,`
`gym: true,`
`roomTypes: ['twin', 'double', 'suite'],`
`checkAvailability: function() {`
`return this.rooms - this.booked;`
`}`
`}`

in an object, functions become known as methods. if a function is called in an object is becomes a method. methods represent tasks that are associated with the object. for examplem you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms.

literal notation is the easiest and most popular way to create objects.

you can access the properties and methods of an object using dot notation, or square brackets.

for example:
`var hotelName = hotel.name;`
`var roomsFree = hotel.checkAvailability();`

now with square brackets:
`var hotelName = hotel['name'];`
`var roomsFree = hotel['checkAvailability']();`

- Creating an object using constructor notation
`var hotel = new Object();`
`hotel.name = 'Dario';`
`hotel.rooms = 9;`
`hotel.booked = 1;`
`hotel.checkAvailability = function() {`
`return this.rooms - this.booked;`
`};`

>DOM (Document Object Model)
as a browser loads a webpage, it creates a model of that page, this is called a DOM tree it stores the browsers memory and consists of four main types of nodes
- document node
- element node
- attribute node
- text node
