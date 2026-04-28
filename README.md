# SuperDevSecurity

Static GitHub Pages site for `superdevsecurity.com`, focused on AI-assisted security research, published work, and public tooling.

## Structure

- `index.html` - home page and current focus areas
- `blog/` - essays, notes, and project writeups
- `research/` - published research and technical reports
- `tools/` - public tooling, demos, and repositories
- `styles.css` - shared site styles
- `script.js` - shared navigation and canvas visualization
- `CNAME` - GitHub Pages custom domain

## Local Preview

Because this is a static site, any simple local web server will work:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Publishing

In GitHub, enable Pages for the repository and select the branch/folder that contains these files. The `CNAME` file is already set to:

```text
superdevsecurity.com
```
