# Loruki Rebuild

<!-- here we have to add more setup things, also i tried different ways to write this long short simple etc...
If you guys have anything to comment please do so.

then ill try to organize this better, following the video proved to be harder than expected in terms of adjusting the planning.
---

<!-- ## User Story Dependencies

[Story Dependency Diagram](https://excalidraw.com/)

---

## WIREFRAME

![wireframe]() -->

---

## 0.Setup

- Create a repository
- Clone the repository
- run `npm install`
- change name of index.html to homepage.html on root

## On homepage.html

on index.css

- add import url to ...
- add `font-family` with a value of 'lato, sans-serif'.
- add `color` with a value of "#333"
- add property of `line-height` with a value of "1.6"

---

## Must have

## 1. Title

_As a user I want to see a title so I can I know website's name._

- This user story is developed on branch `homepage-nav`

- There is a specific title for the website.
- This user story is developed on branch `homepage`.
- This branch is merged to `master` branch after completion.

### Task n1

- use `<title>` tag
- use required checks to make sure codes are right.

### Task n2

- Link a stylesheet to have a `font-family`
- use checks to make sure codes are right

## 2. Navigation bar

**As a user I want to see a navigation bar so I can move to different parts of
the website.**

- This user story is developed on branch `homepage-nav`
- This branch is merged to `master` branch after completion.

### Task n1

On homepage.html

- create a `comment` to separate this section visually
- create a div with class value of `nav bar` for navigation bar
- create a div with a class value of `container flex` to organize the content.
- add a `title` tag and inside include `h1` with "logo" class value. Add text
  value of "Loruki" for `h1`
- create a nav tag with an `unordered list` tag inside with three `list items`
  which contain `a` links to other webpages.
- use required checks to make sure codes are right.

### Task n2

On index.css

- add `font-family` with a value of 'lato, sans-serif'.
- add `color` with a value of "#333"
- add property of `line-height` with a value of "1.6"
- use `border-style` to sets the style of the bottom-driver four borders
- `.ul` with list-style-type set to 'none'
- `.a` with text-decoration set to 'none'; color ser to '#333'
- `.p` with margin set to '10px 0'
- `.img` with width set to '100%'
- `.nav bar` with background-color set to "#047aed";color "#777";height "70px".
- `.container flex` with max-width set to "1100px";margin "0 auto"; overflow
  "auto"; padding "0 40px"
- `.flex` with display set to "flex";justify-content "space between"; align
  items "center"; height "100%"
- `.navbar .flex` with justify content set to "space between"
- `navbar ul` with add display set to "flex"
- `navbar a` with add color set to "#333; add padding "10px"; add margin "0
  5px".
- `navbar a:hover` with border-bottom set to "2px #fff solid"
- use checks to make sure codes are right

### Task n3

## 3. Showcase

_As a user I want to have an input form to request a demo._

- This user story is developed on branch `homepage-showcase`

### Task n1

On homepage.html

<!-- this is the text on the left so im not sure if we should add this here>

- create a `comment` to separate this section visually
- add `section` tag assigning a class value of "showcase"
- add `div` tag with a class value of "container grid"
- add another `div` with class value  "showcase-text"
- add `h1` tag and adding a text value of  "Easier deployment"
- add `p` tag with text value...
- add `a` tag linking it to `features.html` and assigning a class value of "btn btn outline". Also giving a text value inside the tag.

<-->

### Task n2

On homepage.html

-add `div` tag with class value of "showcase-form card" -add `h2` tag with text
value of "Request a Demo" in between. -add a `form` tag -add a `div` with class
value of "form-control". -add a `input` tag with type value of "text", name
value of "name", placeholder of "Name" and make it "required". -add a `div` with
class value of "form-control". -add a `input` tag with type value of "company",
name value of "company", placeholder of "Company" and make it "required". -add a
`div` with class value of "form-control". -add a `input` tag with type value of
"email", name value of "email", placeholder of "Email" and make it "required".
-add a `input` tag with a type value of "submit", name value of "Send" and a
class value of "btn btn-primary"

### Task n3

On index.css

- create a `comment` to separate this section visually.
- add `.showcase` with height value of "400"; background-color "#047aed"; color
  "#fff"; position "relative". -add `.showcase h1` with font size of "40px".
  -add `.showcase p` with margin of "20px 0". -add `.showcase .grid` with
  overflow "visible"; grid-template-columns "55% auto"; gap "30px". -add
  `.showcase-form` with position "relative"; top "60px"; height "350px"; witdth
  "400px"; padding "40px"; z-index "100"; justify-self "flex-end". -add
  `.showcase-form .formcontrol` with margin "30px 0". -add
  `.showcase-form input` with input type set to text; border "0"; border-bottom
  "1px solid #b4ecb"; width "100%"; padding "3px"; font-size "16px". -add
  `showcase-form input:focus` with outline "none".

<!-- Here the video continues the styling of the buttons and showcase responsiveness but thats ouside of must-have's so i left it out to be added after. >
<-->

## 4. Main section or cli

As a user I want to see a main section for the website

- This user story is developed on branch `cli`

### Task n1

On homepage.html

- create a `comment` to separate this section visually. -add `section` tag with
  class value of "cli" -add `div` tag with class value of "container grid" -add
  `img` tag with an image linked from "images" folder. alt value "" -add `div`
  tag with class value of "card" -add `h3` tag with text value in between -add
  another `div` with the same class value of "card". -add `h3` tag with text
  value in between.

### Task n2

On index.css

- create a `comment` to separate this section visually. -add `.cli .grid` with a
  value of grid-template-columns of "repeat(3, 1fr)"; grid-template-rows "repeat
  (2, 1fr)"
  <!-- Don't understand this completely><-->
  -add `.cli .grid` with grid column "1 / span 2"; grid-row "1 / span 2".

## 5. Languages

As a user I want to see which supported languages the site offers.

- This user story is developed on branch `homepage-languages`

### Task n1

- create a `comment` to separate this section visually. -add `section` with
  class value of "languages"
- add `h2` tag with class value of "md text-center my-2" and a text value in
  between tags.
- add `div` with class value of "container flex"
- add `div` with a class value of "card"
- add `h4` tag with text in between tags.
- add `img` tag then link it to a logo on "images" folder.
- create 6 more div with the class "value" and add related tags of `h4` and
  `img`.

### Task n2

-- create a `comment` to separate this section visually. -add `.languages .card`
with text-align "center"; margin "18px 10px 40px". -add `.languages .flex` with
flex-wrap "wrap". -add `.languages .card h4` with font-size "20px"; margin-botto
"10px".

## 6. footer

As a user I want to see a footer where I can find social media account links

- As a user I want to see social media icons and links on the footer.
- This user story is developed on branch `footer`
- This branch is merged to `master` branch after completion.

### Task n1

- create a `comment` to separate this section visually.
- use `footer` with class "footer bg-dark py-5".
- Use `<div>` with class "container grid grid-3" for the links to social media
  accounts
- use `h1` tag and add title name of the footer.
- use `p` tag and add a value in text.
- add `nav` tag with an `ul` tag inside also three `li` and link the pages. -add
  `div` with a class value of "social" -add three `a` tags linked to every
  social media account.

### Task n2

On index.css

- create a `comment` to separate this section visually.
- add `.footer .social` with a value of "margin".
