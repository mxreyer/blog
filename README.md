# Blog

Source of [mxreyer.github.io/blog](https://mxreyer.github.io/blog/): a
plain Jekyll site built by GitHub Pages, using the default `minima` theme.

## Posts

| Date | Post | Code |
| --- | --- | --- |
| 2026-09-04 | [Turning a mining board into a multi-user ML box](_posts/2026-09-04-bc250-ml-box.md) | [pytorch-gpu-bc250](https://github.com/mxreyer/pytorch-gpu-bc250) · [bc250-jupyterhub-opencl-k3s](https://github.com/mxreyer/bc250-jupyterhub-opencl-k3s) |

## Writing a post

1. Add `_posts/YYYY-MM-DD-slug.md` with front matter:
   ```yaml
   ---
   layout: post
   title: "Post title"
   tags: [some, tags]
   ---
   ```
2. Link to code in its own repository with full GitHub URLs; this repo holds
   prose only.
3. Push to `main`. GitHub Pages rebuilds the site; the post appears at
   `https://mxreyer.github.io/blog/<slug>/` and on the home page.

Preview locally, if you have Ruby:

```bash
gem install bundler jekyll github-pages
jekyll serve --baseurl /blog
```

## License

[MIT](LICENSE) — Copyright (c) 2026 mxreyer.
