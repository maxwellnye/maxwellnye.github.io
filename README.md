This is Max's website.

Some thoughts:
This uses the theme minimal-mistakes-jekyll.
You can read about it here:
[https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)

How to use for future Max:
- the sidebar config is stored in `config.yml`
- homepage is simply stored at `index.md` in root folder
- `_data/navigation.yml` controls what other pages are accessable from top-of-page menu bar. I've made drafts of "About", "Publications", and "Blog". These pages are stored in `_pages/`
- I made a blog archive page with test posts. Unused for now, it is commented out in `navigation.yml`
- Protip: it seems that `_site/sitemap.xml` will show all the active pages
- Protip: it seems that adding `published: false` to the front matter will "unpub" a page

How to run:
it should suffice to run `jekyll build --watch` and then `jekyll serve` in the home directory. Then website should be demoable from `http://localhost:4000/`



TODO:
- [ ] add actual content
- [ ] learn markdown
- [ ] add photo
