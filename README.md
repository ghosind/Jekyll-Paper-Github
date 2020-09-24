# Jekyll Paper for Github

![Jekyll Paper](./favicon.ico)

English | [简体中文](./README-CN.md)

Jekyll Paper is a simple Jekyll theme, and it is aim to helping you to create your own blog by the easiest way.

Jekyll Paper for Github is the sub-project for [Jekyll Paper][jekyll-paper], it only contains Github Pages environment supported plugins.

This is a [demo website](https://www.ghosind.com) for Jekyll Paper for Github.

## Features

- Responsive
- Paginate
- RSS
- Sitemap
- Custom 404 page
- SASS
- Internationalization
- Configurable navigation menu
- SEO optimization
- Category Index
- Comments (Disqus)
- Mathematics (MathJax)
- Diagrams (Mermaid)

## Getting Start

Jekyll Paper for Github is easy to create your own blog. You can create your blog by four steps only!

1. Fork your own copy of [Jekyll Paper for Github][jekyll-paper-github] repository to your Github account.
2. Open setting page of your repository.
3. Change repository name to `your_github_username.github.io`.
4. Enter `your_github_name.github.io` in your browser.

## Add New Posts

You can add new posts at any time after you had your own blog. Create a new post need to add a new file in `_posts` directory, and the file name must follow the convention `YYYY-MM-DD-name-of-post.md`.

## Custom Navigation Menu

You can add or update navigation menu items in `_data/menus.yml` file. In the configuration file, you need set title and URL for every navigation menu item.

### Example

```yml
- title: "Index"
  url:   ""

- title: "About"
  url:   "about"
```

## Supported Languages

Jekyll Paper for Github has supported the following languages, please set language in `language` section of `_config.yml` file (default `language: en`). I'm anticipating you to help me improve the quality of translations and add more languages. The languages list by alphabets of its language code.

- English
- Deutsche (German)
- Español (Spanish)
- Français (French)
- 日本語 (Japanese)
- Português (Portuguese)
- 简体中文 (Simplified Chinese)
- 繁體中文 (Traditional Chinese)

## Screenshots

The home page:

![Index Screenshot](./assets/images/index-screenshot.png)

The post page:

![Post Screenshot](./assets/images/post-screenshot.png)

The category page:

![Category Screenshot](./assets/images/category-screenshot.png)

## License

Jekyll Paper for Github was released under MIT license.

## Contributing

If you would like to make Jekyll Paper for Github better, you can create a new pull request in [Jekyll Paper Github Page][jekyll-paper-github].

If you have any questions or suggestions, you can create an issue on [Jekyll Paper for Github Issues][jekyll-paper-github-issues].

[jekyll-paper]: https://github.com/ghosind/Jekyll-Paper
[jekyll-paper-github]: https://github.com/ghosind/Jekyll-Paper-Github
[jekyll-paper-github-issues]: https://github.com/ghosind/Jekyll-Paper-Github/issues
