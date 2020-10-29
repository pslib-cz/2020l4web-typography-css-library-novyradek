# Typography library of Radek Nový
**Author:** Radek Nový
## Demo site
Link to demo site for preview.
## Dependecies
The usage of this library is up to you.
## Implementation
1) Download the css file
2) Insert it to the same folder as your html
3) Copy and paste this part of a code to your header to link the css
```html
<link rel="stylesheet" href="./typography.css"> 
```
4) Download the Roboto font from google fonts (bold/bold italic, medium/medium italic, thin/thin italic)
5) Make sure that the downloaded fonts are in the correct folder
```html
@font-face {
    font-family: "roboto-bold";
    font-weight: 900;
    src: url(./docs/fonts/Roboto-Bold.ttf);
}
```
6) You are ready to go!
## Usage
Make sure to insert the content you want to be affected by this library to **main** tag.
```html
<main>
      (content)
</main>
```
## Components
This library includes:
1) Headings
```html
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
```
2) Paragraphs
```html
<p></p>
```
3) Lists

Unordered list
```html
<ul>
    <li></li>
    <li></li>
            <ul>
                <li></li>
            </ul>
    <li></li>
</ul>
```
Ordered list
```html
<ol>
    <li></li>
    <li></li>
            <ol>
                <li></li>
            </ol>
    <li></li>
</oll>
```
4) Quotes
```html
<q></q>
```
5) Figure
```html
<figure>
    <img src="" alt="">
    <figcaption>image description</figcaption>
</figure>
```
6) Special tags
```html
<s></s>
<small></small>
<b></b>
<em></em>
```

