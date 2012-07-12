---
layout: example
title: Mobify.js Examples
---

# Examples

We've create a few examples to help you get a feel for Mobify.js!

The code is available on Github:

[github.com/mobify/mobifyjs-demos](https://github.com/mobify/mobifyjs-demos)

----

## Demo Store - [demostore.mobify.com](http://demostore.mobify.com)

Uncle Merlin's Discount Potions is a Magento store that uses Mobify.js to 
provide an optimized view for mobile devices.

### Running the Code:

* [Download the code from GitHub](https://github.com/mobify/mobifyjs-demos/zipball/master)

* Unzip the code, navigate to the `demostore` directory and run development server:

        cd demostore && mobify preview

* [Browse to preview.mobify.com to instruct the Mobify.js tag to load the Mobify.js
  file from your local computer. Click "Authorize".](https://preview.mobify.com/?url=http%3A%2F%2Fdemostore.mobify.com)

* If the everything worked you should see the Demo Store mobile adaptation being
  served off your local computer!

### Changing the Code:

With the development server running, you can make updates to the Demo Store 
project files with your text editor and then refresh the page to see your 
changes. Start with these files:

* **src/mobify.konf** contains the DOM operations to select and adapt the source
    DOM. It also contains logic for rendering the template to the browser.

* **src/tmpl/home.tmpl** is the template used to render the homepage. It inherits
    from **src/tmpl/base.tmpl** which is the base template that provides the
    blocks for other templates to override.

* **src/scss/pages/_home.scss*** contains the [SCSS](http://sass-lang.com/) used 
    on the homepage.is where the mobile stylesheets exist. We used SCSS instead of regular

----

## Where to Next?

If you want to understand more about how this stuff works, be sure to check out our 
[documentation](../docs/), and if you have any questions, head over
to our [community](../community/) page.