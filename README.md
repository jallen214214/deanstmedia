# Dean St in the Media

The site at [deanstmedia.com](https://deanstmedia.com): new releases, press and a reading list. A [Dean St](https://deanst.co) project.

It's a single static page (`index.html`) hosted on GitHub Pages. The `CNAME` file points it at deanstmedia.com.

## Updating content

Everything is driven by lists near the top of the `<script>` in `index.html`:

- `RELEASES`: the rotating new-releases carousel, newest first. `ROTATE_SECONDS` sets the timing.
- `PRESS`: the press cards. Keep quotes short and word for word.
- `TOP_PICK` and `SHELF`: the reading section.

Edit, commit and push to `main`. GitHub Pages republishes within a minute or two.

## Preview locally

```bash
python3 -m http.server 8417
```

Then open http://localhost:8417.
