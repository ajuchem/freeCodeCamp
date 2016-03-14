### Instructions

You are given a JSON object representing (a small part of) your record collection. Each album is identified by a unique id number and has several properties. Not all albums have complete information.

Write a function which takes an ```id```, a property (```prop```), and a ```value```.

For the given ```id``` in ```collection```:

If ```value``` is non-blank (```value !== ""```) and ```prop``` is not ```"tracks"``` then update or set the ```value``` for the ```prop```.

If the ```prop``` is ```"tracks"``` and ```value``` is non-blank, push the ```value``` onto the end of the ```tracks``` array.

If ```value``` is blank, delete that ```prop```.

Always return the entire collection object.

####Note
Don't forget to use bracket notation when accessing object properties with variables.
