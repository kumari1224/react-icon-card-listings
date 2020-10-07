# Icons and Card listing
1. Visit for reference: https://create-react-app.dev/docs/deployment/
2. Add `homepage": "https://myusername.github.io/my-app"` anywhere in your package.json.
3. run `npm install --save gh-pages`
4. add `"predeploy": "npm run build", "deploy": "gh-pages -d build",` to your script in package.json
5. now run `npm run deploy` it will publish your project finally.
6. go to your setting and make sure GitHub Pages option in your GitHub project settings is set to use the `gh-pages` branch
7. enjoy !!