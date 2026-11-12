# lpesseygirod.github.io

My portfolio website: **[lpesseygirod.github.io](https://lpesseygirod.github.io)**

I'm Lea, a Computer Science & AI + Business Administration student at IE University in Madrid. This site shows who I am, the projects I build, and how to reach me.

## What's on it

- **Me:** a short introduction, my photo and my CV.
- **Projects:** a page for each project, with what it does, how it works, the stack and a demo you can play:
  - [Sylvie](https://github.com/lpesseygirod/sylvie): my personal AI assistant that runs on my laptop.
  - [KORE](https://github.com/lpesseygirod/kore): a voice companion for older people who speak Spanish.
  - [Survival Council](https://github.com/lpesseygirod/survival-council): an AI that gets $50 and has to pay its own way.
  - [TradeBunny](https://github.com/lpesseygirod/tradebunny): a crypto grid-trading system where I approve every plan.
  - [Studiply](https://github.com/lpesseygirod/studiply): a study app for the iPhone and the web.
- **Skills:** what I work with, and where I've used each one.
- **Contact:** email, LinkedIn and GitHub.

## How it's built

One HTML file, no framework and no build step:

- **Pages without reloading.** Each section is a view, and a few lines of JavaScript switch between them from the URL (`#me`, `#projects`, `#p-sylvie`…), so links and the back button work.
- **The ink background** is a small fluid simulation written in WebGL2: the mouse pours ink that flows and fades, and a few soft drops drift in on their own. On browsers without WebGL2 it falls back to a simpler 2D canvas.
- **The demos** are recordings of the real apps running offline on made-up data (animated WebP), plus screenshots, shown in a small player with captions and play/pause.
- **Light on purpose:** no external scripts, no tracking, no cookies.

## Files

```
index.html     the whole site: HTML, CSS and JavaScript
memoji.png     my memoji on the home page (touch its head)
photo.jpg      my photo on the "Me" page
cv.pdf         my CV
demos/         demo recordings and screenshots for each project
```

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Updating it

Edit `index.html`, commit and push. GitHub Pages publishes the `main` branch, and the change is live within a minute or two.
