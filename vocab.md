# *Words we learned so far:*

## W1D1
* __Stack__: the different technologies and languages to a working web application. Different companies have different "stacks".
* __The Cloud__: the cloud is essentially a computer that holds other 'virtual' computers within it. This is possible because computer processing power is powerful enough that we are able to split up a processor into several 'smaller virtual processors'.
* __Version Control__: a way of keeping track of changes in code across time or developers.
* __Git__: a type of version control that allows us to track changes and go back to previous versions.
* __GitHub__: an online cloud-based software to host git repos.
* __Boilerplate__: a basic set up to work with for any particular web app framework (e.g. Sinatra). 
* __Front End__: the things the user sees - e.g. html, css, javascript
* __Back End__: the code that talks to the database and runs the web server, in our case ruby, rails & active record.
* __Database__: the technology that holds our data to be dynamically displayed on the page by our app.
* __Heroku__: a cloud based service that we can use to host web apps.
* __Open Source__: a type of technology where anyone can view or request a change to the software.
* __IDE__: Integrated Development Environment, a one stop shop for updating code, running your webserver and interacting with the commandline.
* __Cloud9__: our cloud-based IDE of choice for this course. 

## W1D2
* __Tags or Elements__: the different identifiers for HTML to help the web browser know how to interact with them.
* __HTML__: hyper text markup language, the basic structure of web pages.
* __Markup__: another word for html. 
* __Attributes__: Extra invisible mark up that we can add to text to tell the browser how to behave when the user interacts with it, such as the 'href' part of `<a href=""></a>` or the 'src' part of `<img src="">`.
* __Nested tags__: the way that we put one html tag inside the other to build up the structure of the page into sections.
* __The DOM__: the document object model - the way the the way your code and the browser interact.
* __Html tag__: the wrapper for the whole page.
* __Head tag__: information that the browser needs to display the website properly.
* __Body tag__: the content that is drawn to the DOM for the user.
* __Div tag__: a way to divide things on the page. These stack on top of each other by default.
* __Span tag__: a way to divide things on the page. These flow within the content on the page. 
* __Semantic tags__: we should try to use tag names to describe things so that the code is more human readable, and other technologies have an easier time interacting with your page in a meaningful way.  

## W2D1
* __CSS__: Cascading style sheets, or the style language of the web.
* __Selectors__: How we tell css what we want to style, e.g. p, h1, .class, #id etc.
* __Property__: How we tell css what we want to update for that selector.
* __Value__: How we tell css what we want to update that property to.
* __Box model__: The way that css thinks about each element on the page. [see this link for the perfect metaphor for the box model!](https://medium.freecodecamp.org/css-box-model-explained-by-living-in-a-boring-suburban-neighborhood-9a9e692773c1?gi=8dfe07df3608)
* __Padding__: The space within an element.
* __Margin__: The space betweeen an element and other things.
* __Stylesheet__: A collection of css that we can add to the `head` section of our page to apply the style rules within it.
* __Class tag__: A way of linking a style rule to a piece of html.
* __Id tag__: A unique way of linking a style rule to a piece of html. Useful to make sure that you aren't accidentally applying the same rule where you didn't intend to.

## W2D2
* __Ruby__: a programming language - the one we will be using to program our finstagram in!
* __Integers__: A data type in Ruby. Refers to whole numbers e.g. -1, 0, 343, 1828281, -123
* __Floats__: A data type in Ruby. Refers to numbers with decimal points e.g. -1.9912, 0.001, 3.934
* __Booleans__: A data type in Ruby. Can only be true or false.
* __Strings__: A data type in Ruby. The way to store and work with text e.g. “Hi i’m a string”, ‘I\’m also a string’
* __Operators__: The way to do math in programming.
* __Concatination__: Joining strings together.
* __Variables__: How we temporarily store information (not in the database... or at least maybe not yet) so that we can store information for use later in our code.
* __Snake Case__: The way that we name variables in Ruby. Developers are strict about following standards (aka conventions) like this so that it's easier to read each others code. 
* __String Interpolation__: A way to include the result of your variable right into your strin
g! E.g. "Hello, #{first_name} welcome to my fancy customized sentence!". 
* ____: 
* __Control Flow__: The way that we help the computer do if/else logic to make decisions about what to do in a given situation. This is also sometimes call "conditional logic".
* __Methods__: The way to store a set of code that we can reuse at another point in time in our code so that we don't have to repeat ourselves as often. Ruby has a LOT of built in methods that you can use so you don't have to write a bunch of complicated code to do fancy things. In other languages these are sometimes call functions.
* __Argument__: The fancy name for a variable that we use within a method as a placeholder. 
* __Returning__: The name for the end result of what a method "spits out" at the end when it finishes evaluating. Ruby is a bit different than other languages in that the last line of code that runs in a method is the result that the method returns.
* __Hash__: A fancy way to hold data in Ruby so that you can return it later. They are stored in "key value pairs", where the key (that you as a developer can predict) will be on the left, and the value (that may be entered by the user) is stored on the right. This lets us access data from our app in an easy way. Think of it like super organization for your data. 
* __Array__: A list of things - it could be a list of strings, a list of numbers, a list of hashes or even a list of lists (an array of arrays)! You access this by referring it's position in the list, which in programming will ALWAYS start at 0. 

## W3D1
* __ERB__: Embedded Ruby - the way we connect our ruby code to our html to display templates.
* __<%= yield %>__: A special variable that will load in an erb file with "subcontent" into our base html page.
* __Instance variable__: A way to let a variable's data be "seen" by the erb template by adding an `@` symbol in front of the variable name.
* __Alligator tags__: the symbols we wrap our ruby code in within our html so it knows where the html stops and the ruby starts (and vice versa!). For ruby logic, it looks like this: `<% rubycode %>`, and for an individual piece of data we want to show on the page we use `<%= data %>`
* __DRY__: Don't repeat yourself! One of the many reminders to ourselves not to re-type things if we don't have to, because we are ~~lazy~~ efficient.
* __View__: The shorthand term for our ERB file. It means "the thing the user _views_".
* __Actions__: Our list of things to "do" when a certain view is accessed, located in our actions.rb file and broken up into different `get '/something' do ... some code ... end` blocks

## W3D2
* __Database__: A way of storing our data in a way that persists.
* __Persistence__: The idea that data will last beyond the user's time on the page - it's not just stored in the browser, it gets saved in a database for use later.
* __Relational Database__: A way of joining different data sets (called tables) together. 
* __ERD__: Entity relationship diagram - a standard way to visualize the way your database is set up.
* __Primary key__: a unique row in your database.
* __Foreign key__: The way to reference another table in a relational database.
* __One to Many__: One of the types of relations in a relational database.
* __Many to Many__: Another of the types of relations in a relational database.
* __CRUD__: stands for "create", "read", "update" and "delete", the things that you can do when you interface with a database.
* __ORM__: Object Relational Mapper - a way of translating between a coding language and database languages.
* __Active Record__: The language we will use as our ORM that lets Ruby talk to SQL.

## W4D1
* __Query__: The word to describe how to retrieve specific data from a database.
* __Associations__: How we describe relationships between types of data in our database.
* __Class__: The object-oriented way to create objects that has access to methods and contain data.
* __Inheritance__: The way we allow our classes to have access to the methods of other Classes... without having to retype it all.
* __Instance method__: A method that lives within a class. Each "instance" of that class (aka an object) can "call" (use) that method without impacting the way other objects behave.
* __Validations__: How we check that the data being entered into the database for each class meets specific criteria, so that it's nice and clean and tidy in our database.

--------

*Future Classes*


## W4D2
* ____: 

## W5D1
* ____: 

## W5D2
* ____: 

## W6D1
* ____: 

## W6D2
* ____: 
