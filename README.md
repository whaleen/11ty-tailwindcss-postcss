
`npm install`
`npx @11ty/eleventy`
`npm run build-postcss`
Get your hot-loaded lolcathost on
`npx @11ty/eleventy --serve`


## In package.json:

`npm run clean` vaporizes the dist folder

`npm run build-postcss`  runs postcss. Control directories postcss runs on in the package.json scripts. postcss.config.js plugins: autoprefixer and cssnano.


## 11ty config:

.eleventy.js

/src in. /dist out.

Easy to change. The postcss build command needs to respect these locations so edit that too in package.json.


## PostCSS requires

tailwind
autoprefixer
cssnano

You can delete the last two if you don't need them.
