*https://www.theodinproject.com/lessons/foundations-css-foundations*

The **universal selector** will select elements of any type, and the syntax for it is an **asterisk**. 
In the example below, every element would have the color: purple; style applied to it.

*{
    color:purple;
}

A **type selector** (or element selector) will select all elements of the given element type, 
and the syntax is just the name of the element:

div {
  color: white;
}

**Class selectors** will select all elements with the given class, which is just an attribute you place on an HTML element. 
Here’s how you add a class to an HTML tag and select it in CSS:

**index.html**
<div class="alert-text">
  Please agree to our terms of service.
</div>

**styles.css**
.alert-text {
  color: red;
}
