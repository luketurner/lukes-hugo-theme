# Luke's Hugo Theme

This is my Hugo theme for https://blog.luketurner.org/.

Because I consider this a personal theme, it's published without any implication of maintenance or usability for anyone but myself. It has minimal configuration and only supports the features I want. If you wish to use this theme, I recommend forking and modifying it to fit your use case.

## Usage

This theme expects the following content:

- `/content/_index.md` -- contains content for "Home" page, to be displayed above list of recent posts. Can be empty.
- `/content/posts/_index.md` -- contains content for "All Posts" page, to be displayed above categorized list of all posts. Can be empty.

All posts should go under `/content/posts`, using additional subdirectories to categorize posts. The directory structure underneath `/content/posts` can be arbitrarily complex, within reasonable limits.


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

Copyright Luke Turner. Released under MIT License.
