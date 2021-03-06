# Luke's Hugo Theme

This is my Hugo theme for https://blog.luketurner.org. 

Because I consider this a personal theme, it's published without any implication of maintenance or usability for anyone but myself. It has minimal configuration and only supports the features I want. If you wish to use this theme, I recommend forking and modifying it to fit your use case.

More information about the design goals for the theme are available here: https://blog.luketurner.org/posts/blog-theme/.

## Usage

This theme expects the following content:

- `/content/_index.md` -- contains content for "Home" page, to be displayed above list of recent posts. Can be empty.
- `/content/tags/_index.md` -- contains content for "All Tags" page. Can be empty.
- `/content/posts/_index.md` -- contains content for "All Posts" page. Can be empty.

All posts should go under `/content/posts`, with no additional subdirectories. Posts should be organized using the =tag= taxonomy only.


## Configuration

Supports the following configuration parameters, which can be overwritten in your `config.toml`:

``` toml

copyright = "Copyright Luke Turner"
Paginate = 10

[params]
aboutPage = "/posts/writing/blog/about.md"
contactEmail = "admin@luketurner.org"
github = "https://github.com/luketurner"

```

Copyright 2020 Luke Turner. Released under MIT License.
