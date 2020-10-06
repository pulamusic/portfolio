> Jim Carroll |
> jim@pulamusic.com |
> 10/07/2020 |
> [GitHub Profile](https://github.com/pulamusic)

---

## An Instructional Design Portfolio

This is a simple portfolio I am constructing in order to market my skills as an instructional designer. The site has been created using the [Hugo](https://gohugo.io/) static site generator. The layout of the site was adapted from the [Creative Portfolio Theme](https://github.com/kishaningithub/hugo-creative-portfolio-theme) produced by [Kishan B](https://kishaningithub.github.io/).

##### More description to come

---

##### Notes to Self

Figure out how I'm supposed to link the `static/custom.css` file to the header of the theme. It's not clear in the theme's documentation.
* [This article](https://mattmayes.com/posts/2019/hugo-add-custom-css-properly/) might help.

Where do I add my favicon and possibly a logo?

Is there a way to use Google Fonts with this site?

Check out [goldmark](https://github.com/yuin/goldmark/), the Markdown handler for Hugo.
* Also check out [this documentation for setting up the Chroma syntax highlighter](https://gohugo.io/getting-started/configuration-markup#highlight).
* The default style for the highlighter is `monokai`. If I want to change the style, check out [this gallery of Chroma styles](https://xyproto.github.io/splash/docs/longer/all.html) as well as [this page on the configuration of syntax highlighting](https://gohugo.io/content-management/syntax-highlighting/).
* Think about the benefits and challenges of [installing goldmark](go get github.com/yuin/goldmark) for use in other sites and pages.
* Consider adding the [goldmark-emoji extension](https://github.com/yuin/goldmark-emoji#goldmark-emoji) to the list of extensions in `config.toml`.

I've enabled the use of emoticons (see `config.toml`). Here is a link to an [Emoji Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/).
* See note above re: [goldmark-emoji extension](https://github.com/yuin/goldmark-emoji#goldmark-emoji).

Once I have deployed the site, register it with Disqus in order to get a shortname for the site. Add the shortname to the `config.toml` file.

Also register the site with Google Analytics. Add the tracking code to `config.toml`.

Set up the contact form with [formspree.io](https://formspree.io/).
* [Configure the contact form for the Creative Portfolio Theme](https://github.com/kishaningithub/hugo-creative-portfolio-theme#make-the-contact-form-working).

This site has a good collection of [content list templates](https://bwaycer.github.io/hugo_tutorial.hugo/templates/list/).

Check out this page for [formatting dates](https://gohugo.io/functions/format/).

Reconfigure the header info in `work1.md` and use it as a template for the other portfolio pages.
* I've copied the `work1.md` file to a directory on my computer (not in the repo) so I can create a reusable template of my own.

Put together 6 dummy pages with [Unsplash photos](https://unsplash.com/) and [Lorem Ipsum text](https://www.lipsum.com/).
* I have a rough version of `work1.md`. ~~Download some more photos and pump out the dummy pages~~. **Done**

I know the pages are written in Markdown, but is there any trickery I can use to cause links to open in a new tab?

#### A CSS to-do list:
- [ ] Figure out why my site is not exhibiting some of the interactive behaviors the [demo site](https://themes.gohugo.io/theme/hugo-creative-portfolio-theme/portfolio/) has
- [X] Figure out why his social media icons are styled differently
- [X] Does the `custom.css` file override all of the theme's style attributes?
  - Yes it does. Figure out how I can use some of my custom colors anyway. Possibly copy and paste from the theme's css?
- [ ] Change the color and behavior of links
- [ ] Add some padding to the top of the pages
- [ ] Resize and reshape my profile image
- [ ] Choose some different fonts
