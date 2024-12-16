Introducing: Divs

Today, we're exploring an important programming concept related to errors, specifically logic errors. To illustrate this, let’s consider an AI named LittyTron. We want LittyTron to be somewhat beatable, but with a catch: we also want to make it challenging enough for fifth graders to win, as long as they think strategically.

Now, imagine we’re building a Tic Tac Toe app for those fifth graders. Ideally, they'd have a chance to beat LittyTron, but because we mistakenly assume LittyTron should be unbeatable, we inadvertently make the game frustrating and discourage the players from continuing. This unintended outcome, where our code doesn't behave as expected due to incorrect assumptions, is an example of a logic error.

We will engage in some code exploration which will expand our code reading ability to understand the incorrect logic. Once we've obtained an adequate logic understanding, we will modify it in a way that LittyTron can indeed be playable with fifth graders.

Let's start by forking the Starter Code | codepen ). You'll notice it looks pretty boring so far - so let's make our first div!

<body>
	<h1>Div Depot</h1>
	<h3>A playground for divs!</h3>
	
	<!-- 	my first div -->
	<div></div>
  <script src="script.js"></script>
</body>
Notice how there's now a box on the page? That's your div! Usually, divs are blank, empty boxes, but we have done some behind-the-scenes magic to make them more visible for you while you're learning. (This is the same sort of magic you'll be learning in future lessons.)

Like we said before, divs can hold things. So let's try to put a little paragraph of text in there!

<body>
	<h1>Div Depot</h1>
	<h3>A playground for divs!</h3>
	
	<!-- 	my first div -->
	<div>
	   <p>Hello World!</p>
	</div>
  <script src="script.js"></script>
</body>
This paragraph is now inside the div and when you run the program, you should see the text show up inside the div. NB: It may be beneficial when demonstrating this code with your class to also show how it would look if the paragraph was outside the div - both in how it shows up on screen and in how it looks when writing the code.

Now, as you may guess, our divs can hold a lot of things. We can, for example, put more than one paragraph in there:

<!-- 	my first div -->
<div>
    <p>Hello World!</p>
    <p>This div can hold a lot.</p>
</div>
What else can we put in a div? Let's find out!

Make a new div. Put some text in it using h tags in any size you want.
Make a new div. Put an image in it along with a paragraph or two of text.
Make a new div. Put three HTML elements of your choice in it.
{SPICY CHALLENGE} Make a new div. Put a paragraph in it. Then put another div in it. Inside that div, put a second paragraph.
Differentiating Divs: IDs

This is great, but one thing you'll notice is that right now, our divs all look the same. What if we wanted our divs to look differently? There are two ways we can do that: the first is by using IDs. IDs work with CSS - what you'll be covering in the next few lessons - to define specific elements on a page. An ID should only be used for one element that is unique from all others of its type.

Let's say, for example, that we wanted the title of our page to be in a div, and we wanted that div to look different. First, let's put the title in a div:

<!-- 	title div -->
<div>
    <h1>Div Depot</h1>
    <h3>A playground for divs!</h3>
</div>
This should look the same as all the other divs. But let's try giving it an ID:

<!-- 	title div -->
<div id="title">
    <h1>Div Depot</h1>
    <h3>A playground for divs!</h3>
</div>
Quite a bit different, huh? In this instance, we are assuming that the title will just appear in one place and will look unique from all other divs on the page. The styling itself is more behind-the-scenes magic that you'll be learning to do - please note that just adding id="title" won't do anything without that behind-the-scenes work!

Let's test this again: beneath all your other divs, create a new div and fill it with anything you'd like. Give it the id 'footer' and let's see what happens!

Differentiating Divs: Classes

Now let's imagine a page where multiple parts of the page look the same or similar. We want a way to group these so we don't have to repeat ourselves defining their style over and over - but we don't want to use the same ID, because that defeats the purpose of having a unique ID for one unique part of the page.

Let's go back to some of those test divs we made and try adding a class:

<!-- 	my first div - green -->
<div class="green">
    <p>Hello World!</p>
    <p>This div can hold a lot.</p>
</div>
We've made two classes for you: green and yellow. Try adding them to different divs to see what happens!

You'll learn more about divs, ids, and classes as the year goes on - they're all really important and there is a lot you can do with them. They'll be back!

Wrap Up

I believe this was litty so we should go over some of our works answer questions below

What are divs used for?
Why do we utilize classes and IDs?
What questions do you still have about using divs?
Save your codepen and share link
