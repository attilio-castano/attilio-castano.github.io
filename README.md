# Attilio Castano

A personal website with a homepage and individual notes. No build tools,
JavaScript, external fonts, or dependencies are required.

## Local preview

From this directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://127.0.0.1:8000/>. Stop the server with `Ctrl+C`.
You can also open `index.html` directly in a browser.

## Editing

```text
index.html                         Homepage, including the notes list
notes/
  the-world-has-changed.html        First note
  mathematicians-should-read-rick-rubin.html
  formal-methods-renaissance.html
assets/css/
  style.css                        Shared styles for all pages
```

To add a note, create an HTML page in `notes/` and add its link to the Notes
list in `index.html`. Use the existing note as a template. All pages share
`assets/css/style.css`. Changes appear after refreshing the browser.

## Hosting

The site uses GitHub Pages, served from the root of the `main` branch:
<https://attilio-castano.github.io/>.

Pushing changes to `main` publishes an updated site. Preview locally before pushing.
