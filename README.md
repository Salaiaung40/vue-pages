# vue-pages

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

### Creating Vue pages at github pages

see Youtube at https://youtu.be/i_XbW-FsLKk
see https://medium.com/swlh/deploy-vue-app-to-github-pages-2ada48d7397e

"chmod +x deploy.sh" does not work in Windows use "attrib +x deploy.sh"

Remove first "sh" from
["deploy": "sh deploy.sh"] => ["deploy": "deploy.sh"]

ssh key no need in normal situation.

npm run deploy (for running the deploy.sh to create github page)

### Creating main/master resp

#### …or create a new repository on the command line

echo "# vue-pages" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/Salaiaung40/vue-pages.git

git push -u origin main
