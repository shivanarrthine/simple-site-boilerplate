# Simple Site Boilerplate

Boilerplate for static site with node-sass and post-css setup.

## To install:
#### Option 1: Use Github Templates
1. Click the 'Use this template' button on the repo.
2. Enter repo details and create a new repo using this template.
3. After cloning your repo, initialize with `npm install`

#### Option 2: Manual
```
git clone https://github.com/shivanarrthine/simple-site-boilerplate.git
cd simple-site-boilerplate
rm -rf .git && git init
npm install
```

## To compile sass files:
```
npm run watch-css
```

## What's in it?
- Static html page with basic meta tags
- Sass files compiled with node-sass and nodemon
- PostCSS setup
- Autoprefixer and CSS minification
- CSS Reset
- Base CSS styling (eg: tokens, typography)