# 0x06. AirBnB clone - Web dynamic
* How cool it is to request your own API
* How to modify an HTML element style
* How to get and update an HTML element content
* How to modify the DOM
* How to make a GET request with JQuery Ajax
* How to make a POST request with JQuery Ajax
* How to listen/bind to DOM events
* How to listen/bind to user events

## Resources
* Selector
* Get and set content
* Manipulate CSS classes
* Manipulate DOM elements
* Document ready
* Introduction
* GET & POST request
* HTTP access control (CORS)

## Requirements
* Allowed editors: vi, vim, emacs
* All your files will be interpreted on Chrome (version 57.0)
* All your files should end with a new line
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should be semistandard compliant with the flag --global $: semistandard *.js --global $
* All your JavaScript must be in the folder scripts
* You must use JQuery version 3.x
* You are not allowed to use var
* HTML should not reload for each action: DOM manipulation, update values, fetch data…

#### Functionalities of this command interpreter:
* Create a new object (ex: a new User or a new Place)
* Retrieve an object from a file, a database etc...
* Do operations on objects (count, compute stats, etc...)
* Update attributes of an object
* Destroy an object

## Table of Content
* [Environment](#environment)
* [Installation](#installation)
* [Bugs](#bugs)
* [Authors](#authors)
* [License](#license)

## Environment
This project is interpreted/tested on Ubuntu 14.04 LTS using python3 (version 3.4.3)

## Installation
* Clone this repository: `git clone "https://github.com/alexaorrico/AirBnB_clone.git"`
* Access AirBnb directory: `cd AirBnB_clone`
* Run hbnb(interactively): `./console` and enter command
* Run hbnb(non-interactively): `echo "<command>" | ./console.py`

## File Descriptions
[console.py](console.py) - the console contains the entry point of the command interpreter. 
List of commands this console current supports:
* `EOF` - exits console 
* `quit` - exits console
* `<emptyline>` - overwrites default emptyline method and does nothing
* `create` - Creates a new instance of`BaseModel`, saves it (to the JSON file) and prints the id
* `destroy` - Deletes an instance based on the class name and id (save the change into the JSON file). 
* `show` - Prints the string representation of an instance based on the class name and id.
* `all` - Prints all string representation of all instances based or not on the class name. 
* `update` - Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file). 

## Bugs
No known bugs at this time. 

## Authors
Alexa Orrico - [Github](https://github.com/alexaorrico) / [Twitter](https://twitter.com/alexa_orrico)  
Jennifer Huang - [Github](https://github.com/jhuang10123) / [Twitter](https://twitter.com/earthtojhuang)  
Jhoan Zamora - [Github](https://github.com/jzamora5) / [Twitter](https://twitter.com/JhoanZamora10)  
David Ovalle - [Github](https://github.com/Nukemenonai) / [Twitter](https://twitter.com/disartDave)

Abdellatif Hmiche - [Github](https://github.com/Callmevbdu) / [Twitter](https://twitter.com/CallMeVbdu)

Second part of Airbnb: Joann Vuong
## License
Public Domain. No copy write protection. 
