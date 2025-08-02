# coding-project-template

Run
```
npm install
npm run preview
```

Deploy using Github Pages
```bash
npm install gh-pages --save-dev
```

package.json
```yaml
"predeploy": "npm run build",
"deploy": "gh-pages -d dist",
```

vite.config.js
```yaml
base: "/e-plantShopping", # repository name
```

```bash
npm run deploy
```