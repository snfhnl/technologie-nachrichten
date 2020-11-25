# Technologie Nachrichten

This is an example project for a git workshop.

## Dependencies

- [Hugo](https://gohugo.io/)
- [Markdown](https://daringfireball.net/projects/markdown/syntax)

## Getting started

### Add news article

Use the following command to add a new news article:

```
hugo new posts/my-first-post.md
```

### Preview website

Use the following command to preview your changes:

```
hugo server -D
```

This renders the Markdown files and hosts them on a locally running webserver.

See http://localhost:1313/technologie-nachrichten

## Maintenance

### Compile HTML

Use the following command to compile the HTML code from the Markdown files:

```
hugo -D
```

Due to the configuration in [`config.toml`](config.toml), this places the generated HTML code in the [`docs`](docs/) directory.

### Publish website

The website is hosted by GitHub Pages.
So, whenever the HTML code in the [`docs`](docs/) directory changes, the website gets published automatically.

## References

- https://www.heise.de/
- https://news.ycombinator.com/
- https://www.reddit.com/r/java/
- https://www.reddit.com/r/react/

