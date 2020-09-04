# Front-end final mockup-to-website project

Hey everyone! 

This will be our final project in the front-end course, so let's make it a good one :)

First things first, let's get you set up. You will need the following…

## Dependencies

- Node.js
- Figma
- Figma Font Helper

## Install

We'll be using `node-sass` for our Sass compilation. Let's install that by doing:

1. `npm i`

## Getting started

### Source files

Have a look in the `source_materials` folder. There you'll find any fonts you need, images that are required by the design work.

2. Install any OTF/TTF fonts found in the `source_materials/fonts` folder in your system, so that you don't get bugged by Figma's Font replacement dialog box.

### Webroot

As with most setups, it's a good idea to isolate all the web-files in the `webroot` folder.
Export all the images, fonts, HTML, JS, and CSS you use to this webroot folder (in the right subfolder of course!).

3. Create a `webroot/index.html` file.

### Sass

We'll be using the `scss` folder for all our Sass files.

4. Create a `scss/index.scss` file, that will act as our manifest Sass file.
5. Build your CSS file once by running the `npm run scss` script.

All your Sass files will be output to the `webroot/css` folder.

### Linking up our styles

6. Link up the new `webroot/css/index.css` stylesheet in your `index.html`

## Development

You'll want to run the `scss:watch` task when you're developing this project.

## Marking & requirements

You have 5 days to convert the design work to a working single webpage. There's a lot to cover here in a week, and we don't expect you to have the entire website done in that time, but it would be great if you could.

So, what is expected then?

- **All the HTML**
  - Your HTML should be clean, accurate, and consistent.
  - Use the right elements for the right job.
  - Structure your HTML nicely.
  - Make sure your HTML is accessible.
  - Make sure your HTML is valid.
  - *Bonus points*: for progressively enhancing your HTML, e.g. using `<picture>` elements with multiple sources.
- **As much Sass as you can**
  - Your Sass should use variables at a minimum, and be extended with mixins, functions, and abstract classes if you can.
  - Your Sass output should be orderly, and expected.
  - Keep your SCSS files clean
  - Add helpful comments to the difficult-to-understand parts.
  - You don't have to style everything within the time-frame. But we want to see completed components where possible.
- **Images**
  - Are you using a `background-image` or an `<img>` in the HTML? Make sure it's for the right reasons.
  - Use the correct image format for each case
  - *Bonus points*: Compress your images
  - *Bonus points*: Use newer image formats such as WebP and AVIF, while still maintaining support for older formats.
- **Fonts**
  - Link up the WOFF2 and WOFF formats to your CSS using as many `@font-face` at-rules as you need.
  - Use `local()` functions for locally-installed fonts.
  - *Bonus points*: Subset your fonts
- **General**
  - Spelling
  - Testing
  - Don't feel pressure to complete the entire page, but rather try complete each component you start. **Leave out the bits that look too complex to make!**
