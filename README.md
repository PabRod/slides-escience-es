# Template for ready-to-publish obsidian slides

## Why?
I'm an enthousiast user of Obsidian slides.
This repository simplifies, in a **patchy way**, my `edit-publish in GitHub pages-edit again` workflow.

## How to use
1. Press `Use this template` on GitHub. Make sure to allow the creation of a `gh-pages` branch
2. Clone your copy locally
3. Edit `Slides.md` at your convenience
4. Generate the `html`
5. `make update-slides` and voilà, your slides are online at `https://<username>.github.io/<reponame>`

### On images
I didn't manage to make the relative links work.

```sh
# An image linked like
![](./img/example.png)
# will be properly rended locally, but not online
```

Instead, use the following workaround:

```sh
![](https://github.com/<username>/<repository>/blob/main/img/example.png?raw=true)
```

**Note**: the workaround will work locally only after pushing the image to the repository.