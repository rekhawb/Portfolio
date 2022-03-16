# Hello there! Thank you for visiting my portfolio.

<p>&nbsp;</p>
I am Rekha, currently working as an Associate Engineer in a Bio Technology company in Atlanta, GA. I developed interest on coding when I started helping lab techs to decrease their manual efforts in a variety of day to day operations. I have 8+ years of work experience in wide range of technologies like reporting/visualizations like tableau/BO, databases like SQL/Oracle, scripting languages like python, javascript. and industries like power, consumer & industrial and health care.

Coming to HTML , CSS and scripting languages like python and javascript, I did lot of self learning and finally decided to learn it the perfect way. I joined coding bootcamp and it helped me in a big way to write semantic HTML codes and deploy websites that are rich in accessibility and readability.

I am excited about future projects that I will be part of!!!!!

Here is a quick walk through of my portfolio and its building blocks - HTML5 and CSS.<p>&nbsp;</p>

---

<p>&nbsp;</p>

## Portfolio page - (https://rekhawb.github.io/Portfolio/)

You can either click on the image or on the text next to it to navigate to respective sections below.

![](./images/readme_img1.png)

- About me section describes my overall experience, gives information about my current employment and education.

- Projects section lists different projects and technologies that I have worked on. images in the project section
  are created and deployed by me. On hovering the image, you can see enlarged image of the website. and you can
  navigate to the website by clicking the image.

- Contact section lists my email, phone , git hub and current work location.<p>&nbsp;</p>

---

<p>&nbsp;</p>

## index.html

- The html starts with ` <!DOCTYPE html>` to inform the browser what type of document to expect and render accordingly.

- The `<head>` has one of the **_meta_** tags as viewport.This is helpful to adjust the page's display based on the device screen properties.
  It also has links to the css files. **reset.css** is used to reduce default browser settings like line heights, margins, font-sizes etc.,
  in addition to the link to **style.css**, which is specific to the current web page, there is another **href .css** linked
  to import necessary emojis such as phone, email, location and github in the contacts section.

- The `<body>` of the html starts with a `<header>`. the header has navigation links to the sections below. The links are
  placed in the` <nav>` and organised under`<ul>`and `<li>` tags so that screen readers have good and easy accessibility experience.

- After the header , `<main>` starts and there are `<section>` tags in it to hold the cover page image. The cover page image acts a **_flex_** container and it is **_relatively_** positioned so that the portfolio texts and images are overlayed on it. Positioning the
  cover page image relatively also helps the flex container that holds aboutme, projects and contact info sections
  to start right after the image ends.

- Finally the page has a `<footer>` and it holds details about the developer and the year of website creation.

_index.html is created using [HTML](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)_

<p>&nbsp;</p>

---

<p>&nbsp;</p>

## CSS

so we have linked 3 style sheets (.css) to the html.

- .reset.css
- .style.css
- . all.css that are on use.fontawesome.com

- as already mentioned earlier, **_reset.css_** helps to **_reduce browser's default settings_** like margins, font-size's etc.,

- properties like color, font-family etc., that are repeatedly used across the code are defined in the root.

```
:root {
  --sandybrown: #f9a66c;
  --pastelorange: #ffc94b;
  --deepspacesparkle: #f9faf4;
  --center: center;
  --white: rgba(255, 255, 255);
  --headercolor: #21404c;
  --h1shadow: #637981;
```

- coming to the **_style.css_**, all the code is written in **_expanded style_**, with the selector/opening brace, close brace, and each declaration
  on a separate line. majority of the code is written in **_long hand properties_** rather than shorthand properties. These factors maximizes readability.

- all over the css code, you can see **_class selectors_** rather than id selectors as they are less flexible.

- finally **_"mobile first media queries"_** are used. first the styling has been applied to the smaller screens and then
  to the wider screens.
  Here's a code snippet to show **_@media query_**

```
@media screen and (min-width: 768px) and (max-width: 768px) {
 .card-column {
  flex: 0 0 50%;
 max-width: 50%;
  }
 coverpage-row-2 {
  flex: 0 0 50%;
 max-width: 50%;
 }
```

- `display : none ` property is used to show and hide cover page image and about me image based on screen size

- css code is written following the guidelines given on MDN. Complete list of good guidelines can be found here [Good CSS examples on MDN](https://developer.mozilla.org/en-US/docs/MDN/Guidelines/Code_guidelines/CSS)

<p>&nbsp;</p>

---

<p>&nbsp;</p>
