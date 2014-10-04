Jekyllrb with Foundation Test
=============================

## To Run

    git clone git@github.com:liquidvisual/jekyllrb-foundation-test.git
    bundler install
    npm install
    bower install
    grunt serve

This repo is the result of running the [Jekyllrb Yeoman generator](https://github.com/robwierzbowski/generator-jekyllrb) with basic settings.

I've integrated Zurb Foundation 5 in the most basic way (only including the Sass files).

The problem is; the global styles are repeating with every module that is included.I'm not doing anything fancy with the Sass, simply including them as per Zurb's instructions.