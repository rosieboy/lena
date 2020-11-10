# Hugo Greywolf site and Alpha Theme using Tailwind CSS

## Notes from bulding the site and theme

### Package Handler
    This project uses npm

### Hugo
   $ hugo new site greywolf
### Hugo Theme
    $ hugo new theme alpha

### Tailwind CSS
    # Using npm
    $ npm init
    $ npm install tailwindcss postcss-cli autoprefixer
    $ npx tailwind init

### Create the Tailwind configuration file
    $ mkdir assets

### Add the Tailwind UI plugin
    $ npm install @tailwindcss/ui

### Then add @tailwindcss/ui to your Tailwind plugin list:
    # tailwind.config.js

``` js
module.exports = {
  plugins: [
    require('@tailwindcss/ui'),
  ]
}
```

### Build the tailwind CSS file (directive in package.json)
    # After changes to tailwind_directives.css in assets/css
    $ npm run buildtailwind

## Run the server
    $ hugo server --disableFastRender -d ./dist

## Prerequisites

## Usage direcly within a Hugo repo as a theme package

## References