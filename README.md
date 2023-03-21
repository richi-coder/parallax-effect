# Astro Starter Kit: Basics

```
NO NEED TO USE JAVASCRIPT!
```
## Requires patience!

> 🧑‍🚀 **Check the code!**


## 🚀 Project Structure

1.- Create a div class "wrapper" element and set the following CSS to it:
```
.wrapper {
    margin: 0;
    padding: 0;
    width: 100vw;
    height: 100vh;
    overflow-y: auto;
    overflow-x: hidden;
    display: flex;
    flex-direction: column;
    perspective: 10px;
    position: fixed;
    top: 0;
    left: 0;
  }
```

* As you can see, this wrapper element will contain the rest of HTML elements and will be scrolling, instead of scrolling body, main or html.

2.- Create another div inside the "wrapper", call it "sub". Add this CSS to it:
```
.sub {
    display: flex;
    flex-direction: column;
    position: relative;
    height: 100vh;
    transform-style: preserve-3d;
    z-index: -1;
}
```
* This div will containt the element that will produce the parallax effect.

3.- Create two elements to try the effect as next:




/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
