## Table of contents

  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

### What I learned

Display and flexing objects to align them on websites

```css
body {
  background: var(--light-gray);
  font-family: 'Outfit', sans-serif;
  font-size: 15px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: calc(100vh - 1px);
  margin: 1rem;
}
```

Fixing object display sizing

```css
@media (min-width: 500px) {
  .container {
    width: 400px;
  }
}
```

### Useful resources

- [tsbsankara on Youtube](https://www.youtube.com/c/tsbsankara/videos) - Helped me realize the reason the project looked warped was due to my monitor size.

## Author

- Frontend Mentor - [@PinkUv](https://www.frontendmentor.io/profile/PinkUv)