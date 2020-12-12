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
  title: "Blog & Portfolio"
  url: 'https://stisig.github.io/blog/'
  image: widget-1-302x182.jpg
  text: 'Science and technology integration in Emergency Management is a nascent special interest group still defining itself. What sort of EM do you see in the future? With our blog, we highlight recent developments, opinions, and observations from academia and practice.'
widget2:
  title: "Curious About Coding??"
  url: 'https://www.youtube.com/watch?v=LST-LcReOoU&ab_channel=Sweeney732'
  text: 'One aspect of the STI Sig is its focus on gathering tutorials, educational modules, and various kinds of instructional material for the technologically curious. Some of the next-gen competencies for EM include some ability to code (e.g. Java, Javascript, Python). What we're focused on here is not making you an expert, but providing you with terminology and concepts that can help make learning about these things less stressful.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Download Theme"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. Grab the <a href="https://github.com/Phlow/feeling-responsive/tree/bare-bones-version">Bare-Bones-Version</a> for a fresh start or learn how to use it with the <a href="https://github.com/Phlow/feeling-responsive/tree/gh-pages">education-version</a> with sample posts and images. Then tell me via Twitter <a href="http://twitter.com/phlow">@phlow</a>.'
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
  url: https://tinyletter.com/STISIG
  text: Subscribe for monthly updates and news! ›
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
    <iframe width="1280" height="720" src="https://www.youtube.com/watch?v=16gGZ3HdHNk" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
