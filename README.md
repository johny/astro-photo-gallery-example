# A simple example of photo gallery build with Astro

This is a simple example of a photo gallery built with Astro.
Form more details feel free to check my blog post at https://jankraus.net/2024/04/05/how-to-build-a-simple-photo-gallery-with-astro/.

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── content/
│       └── albums/
│           └── album-one/
│               └── cover.jpg
│               └── photo-one.jpg
│               └── ...
│           └── album-one.yml
│           └── ...
│       └── config.ts
│   └── pages/
│       └── index.astro
|       └── gallery.astro
|       └── gallery/
|           └── [id].astro
│   └── components/
│       └── Layout.astro
|   └── utils/
|       └── albums.ts
└── package.json
```

Astro looks for `.astro` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we put any Astro/React/Vue/Svelte/Preact components.

In `src/content/` is where we store our content collections. We have albums with photos and a configuration file for the content collections.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
