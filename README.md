# CSS-buttons

**A question for you: What indications do you see when you are on a website, and you know its a clickable item?**

![Button](https://image.freepik.com/free-vector/colored-website-buttons_23-2147516989.jpg)

This is definately a clickable button. Does anyone disagree?

The thing that makes this look clickable is the definition between the two shades, and the icons. The typography aids us to see that it s a button which will do something when we press it.

![Terrible Buttons](https://ioyby2hf25e3sg55t3muegr1-wpengine.netdna-ssl.com/wp-content/uploads/2015/05/terrible-webdesign-1024x493.png)

What is wrong with this? Why is it hard to see what each element does?

Now that we have a brief insight as to what a button should look like, lets start creating one ourselves.

There is an online tool which I would like everyone to go to and just design a button, this website generates the CSS for you rather than you having to do it. Although it does generate the code for you, take note as to what each line does... it is pretty much a tool in which you can learn.

## HTML and a Button Tag?

Simply enough, there is a tag for a button... Any guesses as to what?

# > <button type="button">Click Me!</button>

> http://css3buttongenerator.com/

> background: #d934c6;

This defines the primary colour. This is the first colour when making a gradient.

> background-image: -webkit-linear-gradient(top, #d934c6, #295a78);
> background-image: -moz-linear-gradient(top, #d934c6, #295a78);
> background-image: -ms-linear-gradient(top, #d934c6, #295a78);
> background-image: -o-linear-gradient(top, #d934c6, #295a78);
> background-image: linear-gradient(to bottom, #d934c6, #295a78);

This line of code is generating the gradient. If you would like just one colour, you would not need to add this as it will be defined by the background colour.

> -webkit-border-radius: 60;
> -moz-border-radius: 60;
> border-radius: 60px;

This line of code is generating the curvature of the button. Try and experiment with it.

> font-family: Arial;

Self explanitory, this defines the font you would like the button to be, ideally the same font as you would have throughout the website.

> color: #ffffff;

The colour of the text, obviously contrasting the button to make sure it is visible.

> font-size: 20px;

This defines the font size. The higher the px, the bigger the button depending on the padding which we will move on to now.

> padding: 40px 40px 40px 40px;

The padding defines the space from the typography to the edge of the buttons. As you can see there is four different numbers.... why? There are four different ones as you can give the button more space on one side if you were to add an icon. **TOP  RIGHT  BOTTOM  LEFT.**

## What about hover state for emphasis?

> .btn:hover {
> background: #3cb0fd;
> background-image: -webkit-linear-gradient(top, #3cb0fd, #3498db);
> background-image: -moz-linear-gradient(top, #3cb0fd, #3498db);
> background-image: -ms-linear-gradient(top, #3cb0fd, #3498db);
> background-image: -o-linear-gradient(top, #3cb0fd, #3498db);
> background-image: linear-gradient(to bottom, #3cb0fd, #3498db);

Majority of what we learnt to define the button is the same. It has the same code but it just defines a different gradient or colour. The background changes when the mouse goes over the button.

**Go to your favourite website, one you visit on a daily basis and see what animations they have to emphasise a button**

