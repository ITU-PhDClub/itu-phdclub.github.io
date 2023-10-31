# ITU PhD Club website
Website for the ITU PhD Club. Uses [hugo](https://gohugo.io/) static site generator with the wowchemy research group theme. 

## HOW-TOs for modifying the site
All content is placed in the `content/` folder. everything is done in a combination of `markdown` and `yaml`.
For markdown, all the standard formatting is supported including a wide range of extensions. look at https://university.wowchemy.com/reference/markdown/ for reference. 

Note that embedding things that refers to other sites might embed that site into ours which could set cookies and such.

all documentation for the theme can be found at https://wowchemy-docs.netlify.app/

### run the site locally

#### installing hugo

git is a prerequisite for hugo so we need to install git if you don't have it, and then hugo.

For git: https://git-scm.com/downloads
for hugo: https://gohugo.io/installation/

##### Windows tl;dr

`winget install --id Git.Git -e --source winget`

`winget install Hugo.Hugo.Extended`


##### MacOS tl;dr (assuming you have homebrew)

`brew install git hugo`

#### Run the site
clone the github project. Navigate to the root folder in a terminal, and then run `hugo server`. It will compile and host the site locally. It will also watch all files and auto-update.

### How do i then add stuff?

If there already exists a type of the content you want to add, you can just duplicate it and update the information. I.e. copy a `authors` folder. Otherwise you can look below to run commands that create templates for you.

### new member
Run `hugo new content/authors/firstname-lastname`

This creates a folder in there with an `_index.md` for the text info and `avatar.jpg` as a default image. Edit the front-matter (the `yaml` part) in the `_index.md` file and overwrite the avatar with a nice image.
  

### new event

Run `hugo new  --kind event event/my-talk-name`

Creates a folder with that name in `content/events/`. You can here just fill it out with the relevant information. Look at older events for inspiration

### new newspost

Run `hugo new  --kind post post/my-article-name`
Creates a post in the `content/post/` folder. You can here just fill it out with the relevant information. Look at older posts for inspiration


## Hugo info
Easily write technical content with plain text Markdown, LaTeX math, diagrams, RMarkdown, or Jupyter, and import publications from BibTeX.

[Check out the latest demo](https://research-group.netlify.app/) of what you'll get in less than 60 seconds, or [view the showcase](https://wowchemy.com/creators/).

The integrated [**Wowchemy**](https://wowchemy.com) website builder and CMS makes it easy to create a beautiful website for free. Edit your site in the CMS (or your favorite editor), generate it with [Hugo](https://github.com/gohugoio/hugo), and deploy with GitHub or Netlify. Customize anything on your site with widgets, light/dark themes, and language packs.

- 👉 [**Get Started**](https://wowchemy.com/hugo-themes/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy research community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- ⬇️ **Automatically import citations from BibTeX** with the [Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli)
- 🐦 Share your new site with the community: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=%23MadeWithWowchemy&src=typed_query)
- 🗳 [Take the survey and help us improve #OpenSource](https://forms.gle/NioD9VhUg7PNmdCAA)
- 🚀 [Contribute improvements](https://github.com/wowchemy/wowchemy-hugo-themes/blob/main/CONTRIBUTING.md) or [suggest improvements](https://github.com/wowchemy/wowchemy-hugo-themes/issues)
- ⬆️ **Updating?** View the [Update Guide](https://wowchemy.com/docs/hugo-tutorials/update/) and [Release Notes](https://github.com/wowchemy/wowchemy-hugo-themes/releases)