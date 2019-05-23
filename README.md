# Reveal-md Playground

Try to write presentations using [reveal-md](https://github.com/webpro/reveal-md).

- Demo-Slidedeck: `demo.md`
- Run: `yarn r`, browser should open automatically in watch mode. if you edit `demo.md` it should update in browser
- Build static sites: `yarn static` (will build html files to `static` folder)

View at GitHub Pages: [https://nilshartmann.github.io/reveal-playground/static/demo.html](https://nilshartmann.github.io/reveal-playground/static/demo.html)

## Todos

- How to specify fragment order (see last page in demo.md)
- google-fonts.css is not loading (css import wrong?)
- how to build html files to root folder instead of `static`
- how to put `md` files in subfolder instead of root
- rebuild all html files at once or individually?
- specifying css or script in markdown does not work when generating static files (https://github.com/webpro/reveal-md/issues/221)
