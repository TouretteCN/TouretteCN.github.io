---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_index.jpg
widget1:
  title: "什么是图雷特综合征?"
  url: '/whatis/'
  image: whatis-cn.png
  text: '图雷特综合症<em>(Tourette Syndrome, TS)</em>是一种神经系统紊乱, 主要表现为不自主的重复性运动和发声。大多数患者于2-21岁之间首次发病，并伴随终生。TS不是退行性疾病，患者的症状通常较为轻微，能够以正常人的愿景生活。<br>本页的视频和文档是对这一疾病的普及性介绍。'

widget2:
  title: "What is Tourette Syndrome?"
  url: '/whatis/'
  text: '<br>Tourette Syndrome is a neurological disorder, which most often begins between the ages of 2 and 21, and lasts throughout life. <br> <br>TS is NOT degenerative and people with TS can expect to live a normal life span. <br> <br>This video is intended for educational purposes.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="/images/introduction-video-500x339.jpg" width="500" height="339" alt=""/></a>'
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
# callforaction:
#   url: https://tinyletter.com/
#   text: Inform me about new updates and features ›
#   style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
sidebar: right
---


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/k0G3T4QNqy0?rel=0&amp;start=2" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
