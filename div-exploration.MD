### Introducing: Divs 

Today, we are learning an important building block for our pages: the div. Divs define a division or a section in an HTML page. We can think of it a bit like an empty box into which we can put other HTML elements to better organize and structure our page. Eventually, you'll learn how divs can be used to create grids and interesting layouts, but today we're keeping it simple.

Let's start by forking the **Starter Code**  | [codepen ](https://codepen.io/jamilton08/pen/jENrpwo)). You'll notice it looks pretty boring so far - so let's make our first div!

```html
<body>
	<h1>Div Depot</h1>
	<h3>A playground for divs!</h3>
	
	<!-- 	my first div -->
	<div></div>
  <script src="script.js"></script>
</body>
```

Notice how there's now a box on the page? That's your div! Usually, divs are blank, empty boxes, but we have done some behind-the-scenes magic to make them more visible for you while you're learning. (This is the same sort of magic you'll be learning in future lessons.)


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

What else can we put in a div? Let's find out! 

* Make a new div. Put some text in it using h tags in any size you want.
* Make a new div. Put an image in it along with a paragraph or two of text.
* Make a new div. Put three HTML elements of your choice in it.
* {SPICY CHALLENGE} Make a new div. Put a paragraph in it. Then put another div in it. Inside that div, put a second paragraph.

---

### Differentiating Divs: IDs 

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

---

### Differentiating Divs: Classes 

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

---

### Wrap Up 

I believe this was litty so we should go over some of our works answer questions below

1. What are divs used for?
2. Why do we utilize classes and IDs?
3. What questions do you still have about using divs?
4. Save your codepen and share link 

