# Day 2 Exercises

## Questions for Ch 3/4

1. There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?

* *Unordered: set of related items in no particular order*

* *Ordered: in specific order*

* *Definition: in name/value pairs*

2. What is the basic structure of an element used to link to another website?

* *"< a href = "url" > text < / a >"*

3. What attribute should you include in a link to open a new tab when the link is clicked?

* *"< a href = "url" target = "_blank" > text < /a >"*

4. How do you link to a specific part of the same page?

* *1. "< a id = "INSERT_YOUR_OBJECT_NAME_HERE" >XYZ< /a >"*
* *2. "< a href = "#INSERT_YOUR_OBJECT_NAME_HERE" > To XYZ < /a >"*


## Questions for Ch 10-12

1. What is the purpose of CSS?

* *Style and layout of webpages, can effect font, color, spacing, columns, animations, other decorations*

2. What does CSS stand for? What does cascading mean in this case?

* *Cascading Style Sheets: cascading is an algorithm which defines how to combine property values from different sources*

3. What is the basic structure of a CSS rule?

```
h1 {
  color: blue;
  background-color: yellow;
  border: 1px solid black;
}
```

4. How do you link a CSS stylesheet to your HTML document?

* *Inline: using style attribute inside HTML elements*
* *Internal: using <style> element in <head>*
* *External: using <link> element to link to external CSS file*

5. When is it useful to use external stylesheets as opposed to using internal CSS?

* *Internal can be used for a single webpage, but external can be used to provide rules for an entire site*

6. Describe what a color hex code is.

* *6 symbol code for colors which references level of red, green, and blue in a color*

7. What are the three parts of an HSL color property?

* *Hue (color), saturation (how vivid/intense), lightness (how light or dark)*

8. In the world of typeface, what are the three main categories of fonts? What are the differences between them?

* *Serif, sans-serif, script (joined letter, cursive)*

9. When specifying font-size, what are the main three units used?

* *Points (12pt), pixels (10px), em (relative to parent element), percent (110%), vw (viewpoint width)*
* *Font-size: x-small/medium/xx-large*
