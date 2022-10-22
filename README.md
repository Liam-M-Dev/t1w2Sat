# A website built from scratch

- html
- css
- wireframes
- git
- markdown

## html

We started creating the skeleton (! + enter in vs code), then we created the header, linked the css and the other two big containers, main and footer.

Header, contains a logo, a heading and navigation

```html
<header>
    <div class="logo">
      <p>
        My Logo
      </p>
    </div>
    <h1>Personal Training</h1>
    <nav class="nav-items">
      <a href="">Training</a>
      <a href="">About Us</a>
      <a href="">Contact</a>
    </nav>
  </header>
```

## CSS

Defined primary and secondary colors, add them to the background and text colors.

Defined flexbox for the header to align the three elements inside centered and vertically.

```css
header {
  background-color: #ff9900;
  display: flex;
  flex-direction: column;
  align-items: center;
}
```
