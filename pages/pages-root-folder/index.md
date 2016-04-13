---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_5.jpg
widget1:
  title: "Biohack Academy"
  url: 'http://yumiNishihara.github.io/about/'
  image: widget-1-302x182.jpg
  text: 'Biohack Academy is an education program of <a href="http://waag.org/en">Waag Society Amsterdam</a>. Held for the first time in the Spring of 2015. The course is fully open source and distributed through partner labs around the globe.'
widget2:
  title: "Weekly Documentation"
  url: 'http://yumiNishihara.github.io/blog/archive/'
  image: widget-1-302x182.jpg
  text: 'Every week we fabricate the hardware necessary for our new bio lab at <a href="https://mtrl.net/shibuya/">FabCafe MTRL</a>. From laser cutting and assembling the pars to soldering the circuits, take a look at our journey of plentiful failures and well earned triumphs.'
widget3:
  title: "Final Project"
  url: 'http://yumiNishihara.github.io/final_project/'
  image: widget-1-302x182.jpg
  text: 'This project is an attempt to collect the microbes both on humans and in the surrounding environment and use it as a living material to grow on jewellery so that it will reflect how we are and where we are.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
