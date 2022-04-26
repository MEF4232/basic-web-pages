# HTML & CSS

https://www.internetingishard.com/html-and-css/

## ✅ Chapter 1 - Introduction

> Think of HTML as the abstract text and images behind a web page, CSS as the page that actually gets displayed, and JavaScript as the behaviors that can manipulate both HTML and CSS. ([Introduction](https://www.internetingishard.com/html-and-css/introduction/#html-css-and-javascript))

## ✅ Chapter 2 - Basic Web Pages

https://www.markdownguide.org/basic-syntax/

https://developer.mozilla.org/en-US/docs/Web/HTML

## ✅ Chapter 3 - Links And Images

> A website is just a collection of HTML files organized into folders. To refer to those files from inside of another file, the Internet uses “uniform resource locators” (URLs). ([Types Of Links](https://www.internetingishard.com/html-and-css/links-and-images/#absolute-relative-and-root-relative-links))

## ✅ Chapter 4 - Hello, CSS

> You can think of Cascading Style Sheets (CSS) as defining the “design” of a web page. It determines things like font size, margins, and colors using a language entirely separate from HTML. ([Hello, CSS](https://www.internetingishard.com/html-and-css/hello-css/))

> The CSS hierarchy for every web page looks like this:
> * The browser’s default stylesheet
> * User-defined stylesheets
> * External stylesheets (that’s us)
> * Page-specific styles (that’s also us)
> * Inline styles (that could be us, but it never should be)
>
> This is ordered from least to most precedence, which means styles defined in each subsequent step override previous ones. ([The Cascade](https://www.internetingishard.com/html-and-css/hello-css/#the-cascade))

## ✅ Chapter 5 - The Box Model

> A couple of very important behaviors associated with block and inline boxes:
> * Block boxes always appear below the previous block element. This is the “natural” or “static” flow of an HTML document when it gets rendered by a web browser.
> * The width of block boxes is set automatically based on the width of its parent container. In this case, our blocks are always the width of the browser window.
> * The default height of block boxes is based on the content it contains. When you narrow the browser window, the &lt;h1&gt; gets split over two lines, and its height adjusts accordingly.
> * Inline boxes don’t affect vertical spacing. They’re not for determining layout—they’re for styling stuff inside of a block.
> * The width of inline boxes is based on the content it contains, not the width of the parent element.
> ([Block Vs Inline](https://www.internetingishard.com/html-and-css/css-box-model/#block-elements-and-inline-elements))

> The “CSS box model” is a set of rules that determine the dimensions of every element in a web page. It gives each box (both inline and block) four properties:
> * Content – The text, image, or other media content in the element.
> * Padding – The space between the box’s content and its border.
> * Border – The line between the box’s padding and margin.
> * Margin – The space between the box and surrounding boxes.
> ([The Box Model](https://www.internetingishard.com/html-and-css/css-box-model/#content-padding-border-and-margin))

> Margins and padding can accomplish the same thing in a lot of situations, making it difficult to determine which one is the “right” choice. The most common reasons why you would pick one over the other are:
> * The padding of a box has a background, while margins are always transparent.
> * Padding is included in the click area of an element, while margins aren’t.
> * Margins collapse vertically, while padding doesn’t.
>
> If none of these help you decide whether to use padding over margin, then don’t fret about it—just pick one. In CSS, there’s often more than one way to solve your problem. ([Margins](https://www.internetingishard.com/html-and-css/css-box-model/#margins))

## ✅ Chapter 6 - CSS Selectors

> Pseudo-classes begin with a colon followed by the name of the desired class. The most common link pseudo-classes are as follows:
> * :link – A link the user has never visited.
> * :visited – A link the user has visited before.
> * :hover – A link with the user’s mouse over it.
> * :active – A link that’s being pressed down by a mouse (or finger). ([Basic Link Styles](https://www.internetingishard.com/html-and-css/css-selectors/#pseudo-classes-for-links))

> Parts of a URL https://example.com/selector.html#button-2
> * Scheme: "https://"
> * Domain: "example.com"
> * Path: "/selector.html"
> * Fragment: "#button-2" ([URL Fragments](https://www.internetingishard.com/html-and-css/css-selectors/#id-selectors))

> Where to start building a new web page:
>
> The separation of content from presentation helps guide this process. You need content before you can present it, so your first step is usually to mark up your raw content with HTML tags. Once that’s prepared, you’re ready to add class attributes to your elements and style them one-by-one. When you discover a need for some extra structure to create a desired layout (e.g., turn a group of elements into a sidebar), that’s when you start wrapping your content in container &lt;div&gt;’s. ([Summary](https://www.internetingishard.com/html-and-css/css-selectors/#summary))

## ✅ Chapter 7 - Floats

> “Floats” let you put block-level elements side-by-side instead of on top of each other. Float-based layouts have mostly been replaced with Flexbox in modern websites. ([Floats](https://www.internetingishard.com/html-and-css/floats/#setup))

> When you have an extra unfloated HTML element at the bottom of a container div, use the clear solution. Otherwise, add an overflow: hidden declaration to the container element. The underlying idea for both options is that you need a way to tell the browser to incorporate floats into the height of their container element in order for their backgrounds to show up. ([Hiding Overflow](https://www.internetingishard.com/html-and-css/floats/#after-a-float))

## ✅ Chapter 8 - Flexbox

> Whereas floats only let us horizontally position our boxes, flexbox gives us complete control over the alignment, direction, order, and size of our boxes...Our recommendation is to use flexbox to lay out your web pages as much as possible, reserving floats for when you need text to flow around a box (i.e., a magazine-style layout) or when you need to support legacy web browsers. ([Flexbox](https://www.internetingishard.com/html-and-css/flexbox/))

## ✅ Chapter 9 - Advanced Positioning

> Take note of that `position: relative;` line. It’s <em>required</em> because only positioned elements pay attention to their z-index property. This is easy to forget, so make a mental note for the next time you’re having depth issues and your CSS rules don’t seem to have any effect. ([Z-Index](https://www.internetingishard.com/html-and-css/advanced-positioning/#z-index

> Relative positioning was for tweaking the position of an element without affecting its surrounding boxes.
>
> Absolute positioning took elements out of the static flow of the page and placed them relative to the browser window, while relatively absolute positioning allowed us to hook back into the static flow of the page.
>
> Finally, fixed positioning let us make elements that didn't scroll with the rest of the page. ([Summary](https://www.internetingishard.com/html-and-css/advanced-positioning/#summary))

## ✅ Chapter 10 - Responsive Design

> Media Queries are written `At-Rule Media-Type AND Media-Feature { CSS-Rules }` ([CSS Media Queries](https://www.internetingishard.com/html-and-css/responsive-design/#css-media-queries))

> A “fluid” layout is one that stretches and shrinks to fill the width of the screen. Fluid layouts let us target a range of screen widths instead of specific mobile devices.
>
> A “fixed-width” layout is the opposite: it has the same width regardless of the screen dimensions. ([Notes on Design](https://www.internetingishard.com/html-and-css/responsive-design/#a-few-notes-on-design))

> Only three components for creating responsive websites:
> - The responsive design (the mockups for each layout)
> - CSS rules for implementing each of those layouts
> - Media queries for conditionally applying those CSS rules. ([Summary](https://www.internetingishard.com/html-and-css/responsive-design/#summary))

## ✅ Chapter 11 - Responsive Images

> To make our images responsive, we have to take three things into consideration:
> - The device’s dimensions
> - The image’s dimensions
> - The device’s screen resolution ([Responsive Images](https://www.internetingishard.com/html-and-css/responsive-images/))

> Only trying to solve two problems:
> - Make images fit into mobile layouts while respecting their intrinsic size
> - Avoid making the user download unnecessarily large image files ([Summary](https://www.internetingishard.com/html-and-css/responsive-images/#summary))

## ✅ Chapter 12 - Semantic HTML

> “Semantic HTML” refers to the idea that all your HTML markup should convey the underlying meaning of your content—not its appearance. ([Semantic HTML](https://www.internetingishard.com/html-and-css/semantic-html/))

## ✅ Chapter 13 - Forms

> There are two aspects of a functional HTML form: the frontend user interface and the backend server. The former is the appearance of the form (as defined by HTML and CSS), while the latter is the code that processes it (storing data in a database, sending an email, etc). ([Forms](https://www.internetingishard.com/html-and-css/forms/))

## ✅ Chapter 14 - Web Typography

> Web typography includes font family, relative font sizes, ident style, text alignment, vertical spacing, and line length. ([Web Typography](https://www.internetingishard.com/html-and-css/web-typography/))

> Web Safe Fonts: a collection of a dozen or so fonts that were pre-installed on most computers. There was no such thing as a custom font file that you could send to browsers to use on your website.
>
> Custom Web Fonts: each browser and device required a different file format (.svg, .eot, .tt, .woff). This resulted in the “Bulletproof @font-face syntax”
>
> The current standard is Web Open Font Format (WOOF) ([A Brief History of Web Fonts](https://www.internetingishard.com/html-and-css/web-typography/#a-brief-history-of-web-fonts))

> A few final guidelines:
> - Use a font-size between 14px and 20px for the body element.
> - Use “curly quotes” and apostrophes with the [& rsquo ;], [& lsquo ;], [& rdquo ;], and [& ldquo ;] HTML entities.
> - Use proper dashes (&ndash;, &mdash;) and other symbols (&copy;).
> - Don’t use text-decoration: underline except for hover states.
> - Use real italic fonts over synthesized ones if not it’s too much of a performance burden. ([Other Guidelines](https://www.internetingishard.com/html-and-css/web-typography/#other-basic-typography-guidelines))

> The most important thing you should take away from this chapter is the fact that nothing is arbitrary in a well-designed web page. The font sizes, indent style, text alignment, line height, margins, and every other tiny facet of the page was carefully considered. There was a purpose behind all of these decisions. ([Summary](https://www.internetingishard.com/html-and-css/web-typography/#summary))

---

## Shortcuts
| Command | Description |
| ------- | ----------- |
| Cmd+T   | search filenames |
| Cmd+R   | reload web browser |
| &lt;!-- test --&gt;| add comments to html |
