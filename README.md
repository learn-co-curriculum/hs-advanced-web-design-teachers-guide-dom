###SWABATs 
+ DOM - explain what the document object model is and how we can interact with it
+ DOM - understand the tree-like structure of the DOM
+ jQuery - use proper syntax
+ jQuery - how to use selectors and methods together to manipulate the DOM
+ jQuery - how to use jQuery selectors - they are essentially the same as CSS selectors
+ jQuery - understand what jQuery is - a library that helps us interact with the DOM
+ jQuery - set up a document with jQuery
whack a mole group project

###Motivation
Yesterday we did a tiny little review of jQuery but you guys didn’t get to really practice. Today is going to be all about solidifying your jQuery skills with a lab and a group project.

###Lesson Plan
+ We started talking about jQuery a little yesterday but let’s go over a few things again.
+ <b>Why do we use jQuery again?</b>
	+ It just works everywhere! jQuery has been written to solve many cross browser issues that exist in core JavaScript.
	+ Terse code. You can often write fewer lines of code than you would in using core JavaScript to accomplish the same thing. Hence jQuery’s slogan “Write Less Do More”.
	+ Popularity. jQuery is currently at the time of writing this by far the most popular JavaScript framework. That means more forums, more code sharing, and more plugins.
	+ Easy extending methods. Coders can create and share their own custom plugins easily.
	+ Familiar DOM selectors. If you already know CSS you’re a step ahead as jQuery uses all our familiar CSS selector statements.
+ <b>How do we get a document set up with jQuery?</b>
+ To setup a document to run jQuery we must link to the jQuery core library first! 
+ Remote link:
`<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js"></script>`
+ Local link (downloaded from jquery.com):
`<script src=”js/jquery-1.8.2.min.js"></script>`
+ <b>What is the DOM?</b>
+ This stands for document object model and it is a structural representation of our HTML in tree form. Like this:
<img src= "https://s3.amazonaws.com/after-school-assets/DOM2.png">
+ How do we manipulate the DOM? Here are a few examples of jQuery selectors we can use:
	+ Select Elements
		+ $('h1')
	+ Select ID
		+ $('#nav')
	+ Select Class
		+ $('.celeb')
	+ Select Attribute
		+ $('a[href^=http://]')
	+ Select Descendent(s)
		+ $('#nav li')
	+ Select Child(ren)
		+ $('#nav > li')
	+ Select Sibling(s)
		+ $('h3 + p')
	+ Select by position
		+ $('li:eq(1)') //selects the second list item
+ And a few examples of jQuery methods:
	+ Effects
		+ animate(), fadeTo(), show(), hide(),  slideToggle()
	+ Events
		+ click(), hover(), focus(), blur(), keypress()
	+ Manipulation
		+ addClass(), clone(), empty(), attr(), val()
	+ Traversing
		+ eq(), each(), has(), closest(), find()
+ Remember there are a TON of jQuery methods and you don’t need to memorize them all. Here is a good resource [http://oscarotero.com/jquery/](http://oscarotero.com/jquery/).
+ Let’s get back into the swing of things with the ATM lab and then this afternoon you guys will be doing a group project - creating a Whac a Mole game!
