# Style "Checkboxes" using CSS custom properties

[![Basic Responsive Menu](http://katheermizal.info/images/projects/additional-works/work-3.png)](http://katheermizal.info/blog/?p=86)

***

- No dependencies
- You guys can download and use this code for your projects
- From the ![heart](http://i.imgur.com/oXJmdtz.gif) of [@katheer](https://twitter.com/ABDULKATHEERMIZ)

***

"input" elements of type checkbox are rendered by default as square boxes that are checked (ticked) when activated, like you might see in an official government paper form. They allow you to select single values for submission in a form (or not).

First, structure the checkboxes on following way

```html
<input type="checkbox" id="checkbox-a" name="checkbox" />
<label for="checkbox-a">...</label>
```
The id attribute on the input, allows us to connect it to the appropriate label using the for attribute. You’ll notice the 2 values are same.

Now user can actually click on the label, and the  checkbox will be selected. It increases our target area. Plus,you can style an element completely differently depending on the state of that checkbox.

```html
input[type='checkbox'] {
    opacity: 0;
}

input[type='checkbox']:checked +label {
    ...
	....
	..
}
```
This is the way custom CSS is working.

***

#### View live demo

[Click Here](http://katheermizal.info/works/working-with-checkbox/index.php)

#### Another working demo on

[Code Pen](https://codepen.io/katheer/pen/jwwNZL)

***
## END...