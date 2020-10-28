---
layout: page
title: Example Page H1
permalink: /example-page/
---
This is an example page.

Here is a link to a kramdown reference: [kramdown: Quick Reference](https://kramdown.gettalong.org/quickref.html)

Inhaltsverzeichnis:
* TOC
{:toc .toc aria-label="Inhaltsverzeichnis"}

## Headlines

Headline Level 2
{: .h2}

Headline Level 3
{: .h3}

Headline Level 4
{: .h4}

Headline Level 5
{: .h5}

Headline Level 6
{: .h6}

## Paragraph

### Normal Paragraph

This is a normal paragraph with filler text. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

### Strong and Emphasized Text
This is a <b>bold word</b> and this is a <strong>strong word</strong>. Here on the other hand you have an <em>emphasized word</em> and an <i>italic word</i>

### Lined Text
Use the u-tag to show text that is <u>not corectly spelled</u>. Use the s-tag to show text that is <s>no longer correct</s>. Use the del-tag to show that a piece of text <del>was deleted</del> and a <ins>new piece of text</ins> was inserted instead.

### Sup and Sub
I can write <sup>superscript</sup> text or <sub>subscript</sub> text.

### Marked Text
This is a paragraph with some <mark>really important highlighted text</mark>.

### Abbreviations
Abbreviations have an own markdown notation, check it out ASAP.

*[ASAP]: as soon as possible

## Link

I can link something like this: [jekyll boilerplate github](https://github.com/Sarah-Lettmann/jekyll-boilerplate)

## Line hr

---

## Lists

### Unordered List

Here is an unordered list
- list item 1
- list item 2
  - second level list item 1
  - second level list item 2
    - third level list item
- A very long list item Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.

### Ordered List

Here is an ordered list
1. list item 1
2. list item 2
    1. second level list item 1
    2. second level list item 2
        1. third level list item
3. A very long list item Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.

### Definition List

This is a term for a definition list
: definition 1
: definition 2

## Images and Figures

### Image

This is a simple image:

![Little Kitten Example Image](/assets/images/kitten.jpg)

### Figure

<figure>
  <img src="/assets/images/kitten 2.jpg" alt="Second Example Image with a little Kitten">
  <figcaption>Figurecaption: A little cute kitten.</figcaption>
</figure>

## Quotes

### Citation

I can cite a creative work like <cite>The Lord of the Rings</cite> with the cite-tag.

### Short Quote

Or I can use the q-tag to mark a short quotation like this:

<q>
The way to get started is to quit talking and begin doing.
</q>

### Block Quote

<blockquote cite="https://blog.hubspot.com/sales/famous-quotes">
  <p>
  The greatest glory in living lies not in never falling, but in rising every time we fall.
  </p>
  <footer>
  Nelson Mandela
  </footer>
</blockquote>

## Table

| Header1 | Header2 | Header3 |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3

## Form Elements

### Input Elements
For more information see [w3schools: HTML input-Tag](https://www.w3schools.com/TAGS/tag_input.asp)

<label>
  Button:
  <input type="button" value="button">
</label>

<label>
  Checkbox:
  <input type="checkbox">
</label>

<label>
  Color:
  <input type="color">
</label>

<label>
  Date:
  <input type="date">
</label>

<label>
  Datetime Local:
  <input type="datetime-local">
</label>

<label>
  Email:
  <input type="email">
</label>

<label>
  File:
  <input type="file">
</label>

<label>
  Hidden:
  <input type="hidden">
</label>

<label>
  Image:
  <input type="image">
</label>

<label>
  Month:
  <input type="month">
</label>

<label>
  Number:
  <input type="number">
</label>

<label>
  Password:
  <input type="password">
</label>

<label>
  Radio:
  <input type="Radio">
</label>

<label>
  Range:
  <input type="Range">
</label>

<label>
  Reset:
  <input type="reset">
</label>

<label>
  Search:
  <input type="search">
</label>

<label>
  Submit:
  <input type="submit">
</label>

<label>
  Tel:
  <input type="tel">
</label>

<label>
  Text:
  <input type="text">
</label>

<label>
  Time:
  <input type="time">
</label>

<label>
  URL:
  <input type="URL">
</label>

<label>
  Week:
  <input type="week">
</label>

### Form and Labeling

<form action="">
  <fieldset>
    <legend>Legend-tag provides a label for the fieldset:</legend>
    <label>
      Text:
      <input type="text">
    </label><br />
    <label>
      Email:
      <input type="email">
    </label>
  </fieldset>
  <label>
    Submit:
    <input type="submit">
  </label>
</form>

### Selects and Datalists

<div>
  <label for="cars">Select:</label>
  <select name="cars" id="cars">
    <optgroup label="Optgroup 1">
      <option value="option1">Option 1</option>
      <option value="option2">Option 2</option>
    </optgroup>
    <optgroup label="Optgroup 2">
      <option value="option1">Option 1</option>
      <option value="option2">Option 2</option>
    </optgroup>
  </select>
</div>

<label for="datalist">Datalist:</label>
<input list="options" name="datalist" id="datalist">
<datalist id="options">
  <option value="Option 1"></option>
  <option value="Option 2"></option>
  <option value="Option 3"></option>
  <option value="Option 4"></option>
  <option value="Option 5"></option>
</datalist>

### Other Elements

<button type="button">Button</button>

<form oninput="x.value=parseInt(a.value)+parseInt(b.value)">
  <label for="x">Output:</label>
  <input type="range" id="a" value="50">
  +<input type="number" id="b" value="25">
  =<output name="x" for="a b"></output>
</form>

<label for="textarea">Textarea:</label>
<textarea name="textarea" rows="4" cols="50">This is an example text.</textarea>

## Code

~~~~~~ css
This is also a code block.
Ending lines must have at least as
many tildes as the starting line.
~~~~~~~~~~~~