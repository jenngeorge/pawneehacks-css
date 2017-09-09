# Style your own landing page

## Setup
- First, open the project in a text editor of your choice (I like Atom).
- Add the style link tag to the `head` section of index.html.
It should look like this
```html
  <link rel="stylesheet" type="text/css" href="styles.css" />
```
- Open `index.html` in Chrome. Select `File > Open File > ...wherever you saved the directory... > pawneehacks-css > style-project > index.html`

Now you're ready to get styling! I've stripped the demo down to a template landing page for you to hack at. Free-style away, or follow the suggestions below to get started:

## Navbar   
  - Try using `float: right` in the `nav-list` class to move the list
of section titles from the left to the right edge of the `nav`
  - Replace the section title placeholders with the names of your sections

## Hero Section
### Text
  - Replace the text in `hero-text` with something more fun
  - Play with `font-size`, `color`, and `font-family` to
customize the `hero-text`. You can find free fonts that likely won't
require any downloading at [Google Fonts](https://fonts.google.com/)
  - Use `position: relative` or `padding` and `margin` to move the
`hero-text` element around inside the `hero` section.
### Image
  - Replace the `background-image` for the `hero` section. Do this
by saving an image and storing it in `style-project/assets`, then
using `background-image: url(assets/your-image.ext)`. You can also
use an image from an online source with
`background-image: url('www.imageurl.com')`

## Additional Information Sections
  - Update these sections to all use either `float` or `flex`
  - Add your own images to the section items in `index.html` like so:
```html
  <img src="assets/my-image.png" alt="my-image" />
  <!-- or -->
  <img src="www.imageurl.com" alt="my-url" />
```

## Bonus
- First, create a [Github](github.com) account if you don't have one
- Publish your site with [Github Pages](https://pages.github.com/)
  - Select 'Project Site', then 'Start from scratch'
