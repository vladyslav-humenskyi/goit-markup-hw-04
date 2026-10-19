# goit-markup-hw-04

GoIT Fullstack HTML/CSS homework #4: **decorative effects**.

The project is the landing page of **WebStudio**, a fictional web studio ("Effective Solutions for Your Business"), built from the course mockup. Each homework in the `goit-markup-hw-0X` series builds on the previous one.

**Live page:** [https://vladyslav-humenskyi.github.io/goit-markup-hw-04/](https://vladyslav-humenskyi.github.io/goit-markup-hw-04/)

## What's done

- SVG sprite (`images/icons.svg`) for feature, social and contact icons, used with `<use>`
- Hero background image with a `linear-gradient` overlay
- Hover and focus effects on links, buttons, team socials and portfolio cards, with CSS transitions
- Flexbox layout and typography carried over from homework #3

## Structure

```
index.html
css/
  main.css        imports all the files below
  common.css      shared styles
  header.css  hero.css  features.css  team.css  portfolio.css  footer.css
images/
  icons.svg       SVG sprite
  hero-bg.jpg     hero background
```

## Run locally

No build step. Open `index.html` in a browser or serve the folder with a static server such as VS Code Live Server.
