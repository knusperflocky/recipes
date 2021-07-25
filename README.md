# [knusperflocky.github.io/recipes](https://knusperflocky.github.io/recipes)

> A fork of recipes plus ones specific to me.

# Development

## Installation

```bash
sudo apt-get install hugo
```

## New recipe
```bash
hugo new posts/recipe-name.md
```

## Hot-reload server
```bash
hugo server -D # includes posts in draft state
```

Pushing to main deploys to github pages.
Remember to remove `draft: true` from content front-matter so that posts will appear in deployed version.

