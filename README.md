A personal tech blog built with [Gatsby](https://www.gatsbyjs.com).

Relies on Gatsby CLI (`npm i -g gatsby`).

---

# Structure

Blog entries are stored in `content/blog/<date>-<title>`, along with images.

Otherwise JS is in `src`, but also `gatsby-*.js` files in root for config.

# Edit

Create a blog entry:

`cp -r content/blog/2021-12-09-welcome content/blog/2199-01-01-goodbye`

Serve with live reload:

`gatsby develop`

# Build

Build:

`gatsby build`

Check:

`gatsby serve`

# Deploy

```
cp -r public/* ../robben1234.github.io

cd ../robben1234.github.io; git add -A .; git commit -m "<title>"; git push; cd ../havrylenkok.com
```


