This is Max's website.

Some thoughts:
This uses the theme minimal-mistakes-jekyll.
You can read about it here:
[https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)

How to use (for future Max):
- the sidebar config is stored in `_config.yml`
- homepage is simply stored at `index.md` in root folder
- `_data/navigation.yml` controls what other pages are accessable from top-of-page menu bar. I've made drafts of "About", "Publications", and "Blog". These pages are stored in `_pages/`
- I made a blog archive page with test posts. Unused for now, it is commented out in `navigation.yml`
- Protip: it seems that `_site/sitemap.xml` will show all the active pages
- Protip: it seems that adding `published: false` to the front matter will "unpub" a page

How to run:
- it should suffice to run `jekyll build --watch` and then `jekyll serve` in the home directory. Then website should be demoable from `http://localhost:4000/`
- nb: now need to run `bundle exec jekyll build --watch` and `bundle exec jekyll serve` bc of switch to github pages
- There's also some business with using jekyll for self hosting vs github pages. I think it only consists of changing lines in `Gemfile` and `_config.yml`. See the quick start guide above for more details. I think in Gemfile, you need to comment out or comment in line `gem` something something, and then the theme needs to be changed in `_config.yml`.


TODO:
- [ ] add actual content
- [ ] learn markdown [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)
- [ ] add photo
- [ ] learn how to make changes without pubbing ... branches?
- [X] ensure it works on maxwellnye.github.io
