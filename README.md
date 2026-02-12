# Shelby's Website
## Notes for Shelby

**NOTE** Until February 4th, 2027, go to https://github.com/kaitersgonnakait/ShelbyPBS.github.io instead to make edits to the website.

### How to make edits to the website
The pages are written using a syntax called Markdown.  Here are more details about how to edit formatting: https://www.markdownguide.org/basic-syntax/

* Homepage -> pages/index.md
* Services -> pages/services.md
* Testimonials -> pages/testimonials.md
* FAQ -> pages/faq.md
* DIY Proofreading -> pages/free-checklists.md
* About -> pages/about.md
* Contact -> pages/contact.md

Your website metadata, such as your business name, email address, etc, are in the `_config.yml` file.

## Kaitln's Notes
Shelby's colors are `#d7efef` and `#cce2cb`.
* `#d7efef` pastel aqua
* `#cce2cb` pastel green

* `#6c9494` darker aqua
* `#719e6f` darker green


### Environment Setup (macos)
Install `chruby`.

```
$ brew install ruby-install chruby
```
Add the following to `~/.zshrc`, making sure to choose the latest version of Ruby in the last line.

```
# enable chruby
source /usr/local/share/chruby/chruby.sh
source /usr/local/share/chruby/auto.sh
chruby ruby-3.3.3
```

Install the latest version of Ruby (at time of writing this is 3.3.3).

```
$ ruby-install ruby 3.3.3
```

Verify this worked by running `ruby -v`.

Run Jekyll for development using the following command:

```
jekyll serve --config _config.yml,_config_dev.yml
```
