# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ False ] `<div><span>hello</div></span>`

b) [ False ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ True ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

A screenreader allows someone who is visually impared to have software read out content in audio format. This is important for web developers as it ensures that the content we produce is accessible to all audiences.

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

html, head, title, body, h1, img

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

html, head, title, body, h1, ul, li, a

c) You want to sell designer hats. You need to receive orders from the user.

html, head, title, body, h1, form, input, submit

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

I did not immediately know the answer to this question but I believe it was answered here: https://stackoverflow.com/questions/39386497/can-i-nest-button-inside-another-button

According to this forum response, interactive content (as defined by w3.org) must NOT have an interactive content descendant. This would include a button inside a button.

## Q5 - What is the most generic tag you can use?

div

## Q6 - What do the following achronyms stand for?

a) `a` - hyperlink

b) `ol` - ordered list

c) `ul` - unordered list

d) `li` - list item

e) `tr` - table row

f) `th` - table header cell

g) `td` - table cell

## Q7 - Usually, `td` elements are children of what kind of elements?

tr

## Q8 - What is the difference between td and th?

td is an ordinary cell in a table
th is a header cell in a table

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1

## Q10 - In which situation can you use self closing tags?

If the element does not need to render any additional html content.

## Q11 - What is autofilling and why is it important?

Autofilling is a feature of modern text editors that helps speed a developers workflow by hinting what code will follow.

## Q12 - Which attributes are always present in an img element?

src, alt

## Q13 - Which attribute is always present for an anchor tag?

href, target