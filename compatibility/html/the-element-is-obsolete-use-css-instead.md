Starting with HTML 4, HTML does not convey styling information anymore (outside the `<style>` element or the `style` attribute of each element). For any new web development project, styling should be written using `CSS` only.

```html
<center>Centered content</center> <!-- Bad: Obsolete center tag -->
Normal text with <font size="+3">larger text</font> inside. <!-- Bad: Obsolete font tag -->
```

# How do I fix this ?

Replace obsolete elements with modern tags and use css to style instead:

```html
<p class="text-center">Paragraph text that is centered correctly</p>
<p>Normal text with <span class="text-large">larger text</span> inside</p>
```
```css
.text-center {
  text-align: center;
}
.text-large {
  font-size: 24px;
}
```

# Resources

* [MDN - Center element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/center)
* [MDN - Font element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/font)
