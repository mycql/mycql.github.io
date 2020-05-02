---
layout: project
type: project
image: images/yapv/puc19.svg
title: Yet Another Plasmid Viewer (YAPV)
permalink: projects/yapv
# All dates must be YYYY-MM-DD format!
date: 2017-03-02
labels:
  - Molecular Biology
  - SVG / Canvas
  - VDOM / Hyperscript
  - React / Vue
summary: A library for creating plasmid feature maps with zero external dependencies.
---

Scientific software tools are 'dinosaurs'. There... I said it. For all the advancements science has made through the years, scientists are still using decades old, commercial software to get their job done. I know because I have long been building user interfaces for bioinformatics tooling for years, starting out with Java based GUI libraries (Swing, SWT anyone remember?) and frameworks (RCP, JavaFX for those who care).

For molecular biologists, one of the most common diagrams they use to represent DNA molecules are feature maps. They are called 'maps' because these diagrams map out locations in a molecule that have significant meaning. Either marking genes of interests, restriction site locations, coding regions and so much more.

YAPV is my attempt at building an open, composable and extensible library for building these maps using modern web technology. I already wrote the geometry so that others don't have to. ^_^ I still plan to add support for other renderers in the future, so stay tuned.

You can learn more at the [YAPV](https://mycql.github.io/yapv) project page.

<iframe width="100%" height="430" src="//jsfiddle.net/mycql/gtk1sybr/46/embedded/result/" allowfullscreen="allowfullscreen" allowpaymentrequest frameborder="0"></iframe>
