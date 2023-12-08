# Public Website

[![Built with Astro](https://astro.badg.es/v1/built-with-astro.svg)](https://astro.build)

## Commands

| Command                | Action                                            |
| :--------------------- | :------------------------------------------------ |
| `npm install`          | Install dependencies                              |
| `npm run dev`          | Start local dev server at `localhost:4321`        |
| `npm run build`        | Build your production site to `./dist/`           |
| `npm run preview`      | Preview your build locally, before deploying      |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check`  |
| `npm run astro --help` | Get help using the Astro CLI                      |
| `npm run format`       | Format code with [Prettier](https://prettier.io/) |
| `npm run clean`        | Remove `node_modules` and build output            |


## Deployment

The site is deployed with Github Pages, which is pointed at the "/docs" directory.
Astro builds the static site in the "/dist" directory, therefore "/docs" is a symbolic link to "/dist".

For domain configuration, refer to:
https://deanattali.com/blog/multiple-github-pages-domains/
