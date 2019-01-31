# mybb.com

The source of the [**MyBB.com**](https://mybb.com) website.

Hosted on [GitHub Pages](https://pages.github.com/) using the [Jekyll](https://jekyllrb.com/) server, [Markdown](https://daringfireball.net/projects/markdown/) formatting, [Liquid](https://shopify.github.io/liquid/) templates, and YAML data format.

Some assets are pulled from the [`mybb-website-theme`](https://github.com/mybb/mybb-website-theme/).

## Development

Clone the repository with `git` and use [Docker](https://www.docker.com/get-started) to serve the website from local source:
```sh
docker run -it --rm -v "$PWD":/usr/src/app -p "4000:4000" mybb/jekyll-docker
```
This will create a container from a [customized Jekyll image](https://github.com/mybb/jekyll-docker). The website will be available at `https://127.0.0.1:4000` (your browser will warn you about an unsigned certificate that was just generated).

## Copyright and Reuse
The website content available in this repository is Copyright 2014 MyBB Group.

While you are welcome to fork this repository to contribute to the development of MyBB's new website, this is the only permitted use for the content within this repository. You may not duplicate, copy, or reuse any portion of the HTML, CSS, Javascript, or visual design elements of the website content available in this repository without express written permission from MyBB except to contribute to the development of MyBB's website. Any other uses are prohibited.
