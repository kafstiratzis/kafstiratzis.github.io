---
date: 2021-03-14
title: 210314 sketching
description: sketching is relaxing
author: Aris Bezas
slug: 210314
tags:
  - p5.js
  - generative art
  - automaton
categories:
  - p5.js
series:
  - Game of Life
---

{{<cover e35zzMesA9I>}}


{{<sketch "210314" >}}
  {{<p5js-embed pixelated>}}
    {{<p5js-file 210314.js>}}
  {{</p5js-embed>}}
{{</sketch>}}



One thing that took some time was hacking p5.js so that I could embed sketches where the canvas scale with the content, so that they could be viewed within the post naturally without worrying about specific sizing of the canvas. This led me to write some [Hugo shortcodes](https://gohugo.io/templates/shortcode-templates/) in order to generate minimal HTML files I could embed within my site, where I had full control over the style (you can check them out on Github). I would like to keep using p5.js in my posts on a regular basis, as it's awesome for drafting some code and producing amazing results, so it is most likely I will write my own minimal editor that I can embed into the blog with JS. I will be using [Svelte](https://svelte.dev/) and going the same route as the official editor by hacking away with the [iframe's srcdoc attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe), that way I can provide fine controls (play, stop, refresh, edit, fullscreen, etc...) and I'll make sure it's open source. If it sounds like something you might be interested in let me know in the comments!

¡Hasta la próxima!

{{<github>}}
