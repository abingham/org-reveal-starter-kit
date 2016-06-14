# org-reveal-starter-kit
Skeleton for creating new `org-reveal`-based presentations

I stole a lot of this from [nwidger](http://nwidger.github.io/blog/post/making-a-reveal.js-presentation-with-org-reveal/)

## Creating a presentation

1. Copy the contents of this repository, but without the `.git` directory.
2. In the top level of that copy, get the [latest version of reveal.js](https://github.com/hakimel/reveal.js/releases). Unzip/unpack the release, and rename the resulting directory to "reveal.js".
3. Edit `presentation.org` and `presentation.css` with your content. Play around with the settings in `presentation.org` as you see fit.
4. Make sure your `org-reveal-root` is set to `./reveal.js` (e.g. `(setq org-reveal-root "./reveal.js")`).
5. Run `org-reveal-export-to-html-and-browse`.

See `presentation.org` for details on what can go in a presentation.
