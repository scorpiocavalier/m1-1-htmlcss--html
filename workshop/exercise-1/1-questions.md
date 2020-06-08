# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ F ] `<div><span>hello</div></span>`

b) [ F ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ T ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

Def: 
    "A screen reader is a software application that enables people with severe visual impairments to use a computer. Screen readers work closely with the computer's Operating System (OS) to provide information about icons, menus, dialogue boxes, files and folders."
    "Semantic HTML gives context to screen readers, which read the contents of a web page out loud."
Source: 
 - https://www.nomensa.com/blog/2005/what-screen-reader
 - https://www.w3schools.com/html/html_accessibility.asp

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

    <html>, <head>, <title>, <body>, <header>, <main>, <ul>, <img>, <footer>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

    <html>, <head>, <title>, <body>, <header>, <main>, <ul>, <a>, <img>, <footer>

c) You want to sell designer hats. You need to receive orders from the user.

    <html>, <head>, <title>, <body>, <header>, <nav>, <main>, <ul>, <a>, <img>, <button>, <aside>, <footer>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

    It is not valid to have a button tag as a child of another button tag. A button tag can only have text and/or non-interactive tags.

## Q5 - What is the most generic tag you can use?

    <div>

## Q6 - What do the following achronyms stand for?

a) `a` -> hyperlink anchor

b) `ol` -> ordered list

c) `ul` -> unordered list

d) `li` -> list item

e) `tr` -> table row

f) `th` -> table header

g) `td` -> table data element

## Q7 - Usually, `td` elements are children of what kind of elements?

    <td> elements are children of <tr> and <table>

## Q8 - What is the difference between td and th?

    <th> elements are used as headers and are usually bigger, bolded and centered.
    <td> elements are used to display data in a table and are in standard font.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

    <h1> is the bigger of the two. <h1> and <h3> make text appear bigger and bolder than regular text inside a <p> without extra styling.

## Q10 - In which situation can you use self closing tags?

    Some tags can be used with self closing tags when there is no other content that need nesting, such as <img/> or <link/> and are considered "void-elements" in HTML spec. Since HTML5, closing tags are optional but is preferred.

## Q11 - What is autofilling and why is it important?

    Autofilling can help speed your coding as it will finish your initial typing for you. You might have more than one option to choose from when it occurs. It can also help avoid typos, resulting in less bugs to worried about.

## Q12 - Which attributes are always present in an img element?

    Inside an <img> tag, the 'src' and 'alt' attributes are always present to show the image and provide accessibility.

## Q13 - Which attribute is always present for an anchor tag?

    Inside an <a> tag, the 'href' is always present to provide the link address.
