# martinkaptein.com
Repository of [martinkaptein.com](https://www.martinkaptein.com/).

Currently using Hugo 0.37.1. Build, deployed and hosted by Netlify.

Theme: hyde-hyde

Original theme can be found [here](https://github.com/htr3n/hyde-hyde)

## Usage

New static page:

`hugo new page/pagename.md`

New blog entry:

`hugo new blog/blog-slug.md`

## Mods to theme

Check theme `/layouts/index.html`

`"posts" >> "blog"` in order for root page to work correctly.

hotfix for date issue:
in main `config.toml` under `params` 
`dateformat = "Jan 1, 2006" >> dateformat = "Jan 2, 2006"`