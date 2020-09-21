# Parchment
A clean, single column blog template built for jekyll

## Building Locally
* Clone the repository
* Run `bundle install`
* Run `bundle exec jekyll serve`
* Visit browser at `http://127.0.0.1:4000/`

## Usage
* easy way to set up a free site for yourself using github and cloudflare. I followed a mix of the following:
1. [freecodecamp](https://www.freecodecamp.org/news/an-illustrated-guide-for-setting-up-your-website-using-github-cloudflare-5a7a11ca9465/)
2. [Landon Patmore](https://www.codementor.io/@landonpatmore/how-to-setup-a-static-website-using-github-pages-and-cloudflare-with-your-own-domain-name-jb99nbuoe)
3. [Sam Dutton](https://medium.com/@samdutton/github-pages-cloudflare-custom-domain-checklist-e86c786194a4)

* To use this as your GitHub Page, fork this repository, and
  rename it to `<username>.github.io`. Your site will be live
  at `https://<username>.github.io/`.

* You can customise variables in `_config.yml` and `css/*` files.

* You can add markdown files, say `foo.md` in the root directory
  of the repository. It will then be accessible like
  `your.website.com/foo`.

* To add posts, add your posts in the `_posts` directory. Follow
  the naming convention `%yyyy-%mm-%dd-your-title-here.md`.

* To add a profile picture, use class `profile-picture` around
  the image.

* My setup on a mac using Std user without Homebrew or Macports:install xcode, [add your user to sudo](https://stuntcoders.com/add-user-to-sudoers-on-mac-os-x/), clone the repo, follow  instructions from above. [Also using atom](https://atom.io) which is great for this.

## Credits
Forked rom [Parchment](https://github.com/pro-panda/parchment) by pro-panda which was inspired from the resume theme
[Researcher](https://github.com/ankitsultana/researcher)

## License
[GNU GPL v3](LICENSE)
