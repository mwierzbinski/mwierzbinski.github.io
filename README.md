# The coding bear blog. 
The Coding bear blog is my place to document the stuff I learn. Currently it is based on [Jekyll][1] [Cayman theme][4] and hosted on [GitHub Pages][3]. Mainly because it was one of the simplest and cleanest looking themes I could find. Thanks [@jasonlong][2] for creating it!.

# Cayman theme
## Setup

Some important configuration can be done in the file `_config.yml`. Please, check the Setup section in that file.

### baseurl

`baseurl` parameter is required in the case the site doesn't sit on the root of the domain. For example: http://pietromenna.github.io/jekyll-cayman-theme

In the case above the baseurl should be set to "/jekyll-cayman-theme".

In the case the site sits in the root, you can leave `baseurl` as empty "".

## Development

To set up your environment to develop this theme, run `bundle install`.

You theme is setup just like a normal Jelyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/) license.

[1]: http://jekyllrb.com/
[2]: https://github.com/jasonlong
[3]: http://pages.github.com/
[4]: https://github.com/jasonlong/cayman-theme