class: center, middle, inverse, title-slide

# Markdown Presentation Starter
### Dan Tullis

---
layout: true
background-image: url(./assets/images/bg.png)
background-position: 0% 0%
.footer[Markdown .red[Presentation] Starter]

---
.left-column[]
.right-column[
## Layout With Background Image
A simple, _in-browser_, Markdown-driven slideshow tool  
targeted at people who know their way around HTML  
and CSS, featuring:

- Markdown .red[formatting], with smart extensions

- `Presenter mode`, with cloned slideshow view

- Syntax .yellow-bgc[highlighting], supporting a range of languages

- Slide scaling, thus similar appearance on all devices / resolutions

- Touch support for smart phones and pads, i.e. swipe to navigate slides
]

---
layout: false
class: inverse

# Keyboard Shortcuts
.large[
- `?` or `h`: Toggle the help window

- `→` : Go to next slide

- `←` : Go to previous slide

- `c`: Clone presentation to a new window

- `p`: Toggle presenter mode

- `f`: Togggle full screen mode

- `t`: Start/stop timer

- `number + return`: Go to page `number`
]
.footer[Markdown .red[Presentation] Starter]

---
layout: true
background-image: url(./assets/images/bg.png)
background-position: 0% 0%
.footer[Markdown .red[Presentation] Starter]

---
.left-column[]
.right-column[
# View Notes In Presentation Mode
This is random presentation content.  

To see any notes associated with this slide press the `p` key to enter `Presentation Mode`.  

Note: Ensure you started via `npm run presentation` and all _default web browsers are closed_.  

To create notes type three question marks followed by the note text:
```markdown
???
These are the notes for this slide.
```
]

???
These are the notes for this slide.

---
layout: false

# Two dashes

The easiest way to build incremental slides is...  
--
   

 to use two dashes `--` to separate content on a slide.

--

You can divide a slide in _any way you want_.

--

- One bullet

--

- Another bullet

--

- And one more
.footer[Markdown .red[Presentation] Starter]

---
layout: true
background-image: url(./assets/images/bg.png)
background-position: 0% 0%
.footer[Markdown .red[Presentation] Starter]

---
.left-column[]
.right-column[
# Code Blocks

Java code block:
```java
static void myMethod() {
  System.out.println("hello");
}
```

JavaScript code block:
```javascript
function add(a, b)
  return a + b
end
```
]

---
.left-column[]
.right-column[
# Highlight In Code Blocks

Highlight by using a leading `*`:

```markdown
*Highlighted
```

```c
if (a == b) {
** a + b
}
```

Output:
```c
if (a == b) {
* a + b
}
```
]

---
.left-column[]
.right-column[
[//]: # ( this is a hidden comment )  
# Hidden Comments  

To create a hidden comment:
```sh
[//]: # ( the comment )
```
]

---
.left-column[]
.right-column[
## MathJax
To create the `equation` below:  
`\(\color{blue} {\frac{a}{\color{red} b} \sqrt{\color{black} x}}\)`

Enter the following:
```latex
`\(\color{blue} {\frac{a}{\color{red} b} \sqrt{\color{black} x}}\)`
```
]

---
layout: false
class: center, middle, inverse

**[Markdown Presentation Starter](https://github.com/dantullis/markdown-presentation-starter)**  
Created with:  
**[RemarkJs.com](https://www.remarkjs.com)**  
**[Live-Server](https://github.com/tapio/live-server)**  
**[MathJax.org](https://www.mathjax.org/)**  
**[DeckTape](https://github.com/astefanutti/decktape)**

--
##### Any Suggestions / Issues?
https://github.com/dantullis/markdown-presentation-starter/issues