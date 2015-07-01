https://elements.polymer-project.org/elements/google-feeds

this element could be the core of polymer app..  it is a component to
of my overall design. 

Example:

<template is='dom-bind'>
  <google-feeds feed='http://www.engadget.com/rss-full.xml'
  results='{{result}}'></google-feeds>
  <p>Feed title: <span>{{result.title}}</span></p>
</template>

