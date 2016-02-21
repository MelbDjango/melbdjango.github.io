
# Melb Django

To be served static on Github Pages.

## Developing Locally

```
  npm install
  npm start
```

This will:

- watch files in the styles/ directory for changes, 
- compile styles.scss to a .tmp/ directory
- run autoprefixer over the compiled temp files
- pass the prefixed file through clean-css, resuting in dist/styles.min.css
- serve the files using browser-sync, and refresh on changes
