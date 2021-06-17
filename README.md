# Garden Tools

Simple bootstrap-esque component and style library.

**Actions:**  

npm run dev | Starts the project and opens the index page.

npm run deploy | Output a complete minified production build.

**Do we need to include a special compile function that is different that DEPLOY so we can have a CSS file always ready to go??**

Tools:
  - Fonts
  - Forms
  - Global
  - Index
  - Typography
  - variables
  - page

How to use the tools:

Install the tools
  - npm install gardentools

Include either the uncompiled or compiled versions of the garden tools. Do your best to only include the SCSS tools into stylesheets and the JS tools into JS script files.

In your main style sheet (brings in stylesheets). You can include index.scss to get everything or include the individual stylesheets named above.

@import "topiary-tools/scss/index.scss";


If you plan to use any form components you will need to import the appropriate JS files. Importing the index file will give you access to everything.

@import "topiary-tools/scrips/index.js";



***Node Package Manager***
This repo is the source for the NPM package topiary -tools found in NPMJS.com.
