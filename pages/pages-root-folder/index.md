---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "About meaning"
  url: '/about/'
  image: widget-1-302x182.jpg
  text: 'There is a lot of talk about AI, these days. Not so much about meaning. And still, AI without meaning will not reach intelligence.'
widget2:
  title: "AI in the Woods"
  url: '/aiinthewoods/'
  text: 'What is AI, really? What does it have to do with meaning? Come and find out in the woods.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="./images/start-video-feeling-responsive-302x182.jpg" alt="" style="width:100%"/></a>'
widget3:
  title: "Blog"
  url: '/blog/'
  image: widget-3-303x182.jpg
  text: 'The <em>Denotation</em> blog offers the latest content on meaning, linguistics and Artificial Intelligence.'
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
callforaction:
  url: /subscribe/
  text: Sign up for the Denotation newsletter ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/785975640?h=92dba22ea4&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="AI in the woods - introduction"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
