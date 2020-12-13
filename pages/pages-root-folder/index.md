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
  title: "The STI SIG Blog"
  url: 'https://stisig.github.io/blog/'
  image: widget-1-302x182.jpg
  text: 'What sort of EM do you see in the future? What sort of technology does that version of EM use? How do we actually get on a path that would allow us to be able to realize that version? A major component of this SIG is to advocate and demonstrate potential futures, technologies, and ways to bridge academics who are developing technology with emergency management practitioners who can deploy it. Our blog allows us to do just that by highlighting recent developments, opinions, and observations from academia and practice. Opinions expressed here are made by the blog author alone.'
widget2:
  title: "Curious about Coding?"
  url: 'https://stisig.github.io/coding/'
  text: 'An important activity for this SIG is the pursuit of ways to teach how programming works. This includes ways for you to teach yourselves. At first, these will be rough, course notes from Dr. LaLone&#8217;s past courses. However, over time these will become closer to how EM needs programming to work, and how that need can generate ways of learning. Click above for a brief introduction to this content.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "SIG Administration and Integration Philosophies"
  url: 'https://github.com/STISIG/Administration'
  image: widget-github-303x182.jpg
  text: 'Since this is a SIG for the FEMA Higher Education Program, we meet regularly--typically on the first Thursday of each month. The minutes for these meetings will be located in our repository. In addition to those meeting notes, we will irregularly produce white papers and bits of philosophy about how to best advocate for more integrative progress in EM. This could include everything from how to broach the need for technology training to policy creation for social media use.'
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
  text: Subscribe to our newsletter for monthly updates! ›
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3whFBvMajEk" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
