### Introducing: Divs 

Today, we are learning an important building block for our pages: the div. Divs define a division or a section in an HTML page. We can think of it a bit like an empty box into which we can put other HTML elements to better organize and structure our page. Eventually, you'll learn how divs can be used to create grids and interesting layouts, but today we're keeping it simple.

Let's start by forking the **Starter Code** ([repl.it](https://replit.com/@qrtnycs4all/Interactive-Web-U1LA12-Divs-Class-IDs-Starter-Code#index.html) | [github](https://github.com/nycdoe-cs4all/interactive-web/tree/main/unit-1-html-and-css-good-vs-bad-design/U1LA1.2/Starter%20Code)). You'll notice it looks pretty boring so far - so let's make our first div!

```html
<body>
	<h1>Div Depot</h1>
	<h3>A playground for divs!</h3>
	
	<!-- 	my first div -->
	<div></div>
  <script src="script.js"></script>
</body>
```
---
Notice how there's now a box on the page? That's your div! Usually, divs are blank, empty boxes, but we have done some behind-the-scenes magic to make them more visible for you while you're learning. (This is the same sort of magic you'll be learning in future lessons.)

**NB:** _Leaving comments here is important, as students will be making A LOT of divs and then adding things inside of them. Having comments to differentiate between them is very helpful!_

Like we said before, divs can hold things. So let's try to put a little paragraph of text in there!

```html
<body>
	<h1>Div Depot</h1>
	<h3>A playground for divs!</h3>
	
	<!-- 	my first div -->
	<div>
	   <p>Hello World!</p>
	</div>
  <script src="script.js"></script>
</body>
```

This paragraph is now _inside_ the div and when you run the program, you should see the text show up _inside_ the div. **NB:** _It may be beneficial when demonstrating this code with your class to also show how it would look if the paragraph was_ outside _the div - both in how it shows up on screen and in how it looks when writing the code._

Now, as you may guess, our divs can hold a lot of things. We can, for example, put more than one paragraph in there:

```html
<!-- 	my first div -->
<div>
    <p>Hello World!</p>
    <p>This div can hold a lot.</p>
</div>
```

What else can we put in a div? Let's find out! Give students about 7-10 minutes to complete a few or all of the following:

* Make a new div. Put some text in it using h tags in any size they want.
* Make a new div. Put an image in it along with a paragraph or two of text.
* Make a new div. Put three HTML elements of your choice in it.
* {SPICY CHALLENGE} Make a new div. Put a paragraph in it. Then put another div in it. Inside that div, put a second paragraph.

Once students are done, spend some time reviewing what they have made - you may ask students to display their code, to come up to your computer and complete your code on the screen, or to walk you through what to type to solve one or more of the tasks. Make sure that if no one got to the spicy challenge, you spend time looking at it together, as placing divs inside of divs will become important as students continue their web development journey.

### Differentiating Divs: IDs (\~5 - 7 min)

This is great, but one thing you'll notice is that right now, our divs all look the same. What if we wanted our divs to look differently? There are two ways we can do that: the first is by using IDs. IDs work with CSS - what you'll be covering in the next few lessons - to define _specific_ elements on a page. An ID should only be used for one element that is unique from all others of its type.

Let's say, for example, that we wanted the title of our page to be in a div, and we wanted that div to look different. First, let's put the title in a div:

```html
<!-- 	title div -->
<div>
    <h1>Div Depot</h1>
    <h3>A playground for divs!</h3>
</div>
```

This should look the same as all the other divs. But let's try giving it an ID:

```html
<!-- 	title div -->
<div id="title">
    <h1>Div Depot</h1>
    <h3>A playground for divs!</h3>
</div>
```

Quite a bit different, huh? In this instance, we are assuming that the title will just appear in one place and will look unique from all other divs on the page. The styling itself is more behind-the-scenes magic that you'll be learning to do - please note that just adding id="title" won't do anything without that behind-the-scenes work!

Let's test this again: beneath all your other divs, create a new div and fill it with anything you'd like. Give it the id 'footer' and let's see what happens!

### Differentiating Divs: Classes (\~5 - 7 min)

Now let's imagine a page where multiple parts of the page look the same or similar. We want a way to group these so we don't have to repeat ourselves defining their style over and over - but we don't want to use the same ID, because that defeats the purpose of _having_ a unique ID for one unique part of the page.&#x20;

Let's go back to some of those test divs we made and try adding a class:

```html
<!-- 	my first div - green -->
<div class="green">
    <p>Hello World!</p>
    <p>This div can hold a lot.</p>
</div>
```

We've made two classes for you: green and yellow. Try adding them to different divs to see what happens!

You'll learn more about divs, ids, and classes as the year goes on - they're all really important and there is a lot you can do with them. They'll be back!

### Wrap Up (\~5 min)

As a final wrap-up, it may be helpful to once again have students display some of the code they have created. You may also want to ask one or all of the following - either for a brief discussion or to collect as a post-it note check-in/exit slip:

1. What are divs used for?
2. Why do we utilize classes and IDs?
3. What questions do you still have about using divs?

### Extensions

The hardest part of working with divs - and HTML generally - is nesting elements inside each other. The more students can get used to doing that now (think div inception) the better off they will be in the future. Soak up this time to practice doing challenging things with simple tools before we continue to add on!
