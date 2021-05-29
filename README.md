# gitpod-starter-html

If you want to use a folder and preview the html inside of them, you will need to change the `package.json` file like this:

```json
"scripts": {
    "serve-gitpod": "cd folder_name && browser-sync --watch --server --no-open --no-ui --listen 0.0.0.0",
    "serve": "cd folder_name && browser-sync -f *.html -f *.js -f *.css""
}
```

