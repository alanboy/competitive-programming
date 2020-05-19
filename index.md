---
layout: default
title: UWBCP
---

## What is competitive programming?

Competitive programming is a mind sport usually held over the Internet or a local network, involving participants trying to write computer programs capable of solving a set of logical or mathematical problems. Judging is based mostly upon number of problems solved and time spent for writing successful solutions, but may also include other factors (quality of output produced, execution time, program size, etc.)

Competitive programming is recognized and supported by several multinational software and Internet companies, such as Google and Facebook. There are several organizations who host programming competitions on a regular basis.

## Upcoming Events

You can find list of events held this quarter [<span style = "color:blue">here</span>](/events.md). The document would be updated accordingly each quarter with new events. Stay tuned to this page!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{post.url}}">{{post.title}}</a>
    </li>
  {% endfor %}
</ul>
