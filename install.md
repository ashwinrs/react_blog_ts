```
create-react-app react_blog_ts --scripts-version=react-scripts-ts


// deploy commands
npm run build
npm run deploy

// installing gh-pages plugin
add this to package.json
  "homepage": "https://ashwinrs.github.io/<repo_name>",
  // add under scripts
  "deploy" : "npm run build&&gh-pages -d build"

npm install --save-dev gh-pages

// installing react markdown
npm install --save react-markdown

```