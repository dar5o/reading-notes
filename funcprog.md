> functional programming

functional programming is basically a style of building the structure and elements of computer programs. it treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

a pure function is something that returns the same resulty if given the same arguments (also called deterministic) we know if something is a pure function of it does not cause any observable side effects

the benefits of a pure function include: stable, consistent and predictable functions. given the same parameters, pure functions will always return the same result

immutability is best described when a data's state cannot be changed after its created

referential transparency is when a function consistently yields the same result for the same input

**pure functions + immutable data = referential transparency**

> node.js

a module is essentially any JS file that contributes to another file

the word require returns the exported data from what is being passed into the require function

`let aVar = require('./pathToTheVar')` will bring in another module into the file we are working in

`module.exports = thingToExportFromFile` will make the module available


