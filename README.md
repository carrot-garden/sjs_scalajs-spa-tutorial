# Scala.js SPA-tutorial

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ochrons/scalajs-spa-tutorial?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Scala.js](https://www.scala-js.org/assets/badges/scalajs-0.6.13.svg)](https://www.scala-js.org)

Tutorial for creating a simple (but potentially complex!) Single Page Application with
[Scala.js](http://www.scala-js.org/) and [Play](https://www.playframework.com/).

## Purpose

This project demonstrates typical design patterns and practices for developing SPAs with Scala.js with special focus on
building a complete application. It started as a way to learn more about Scala.js and related libraries, but then I
decided to make it more tutorial-like for the greater good :)

The code covers typical aspects of building a SPA using Scala.js but it doesn't try to be an all-encompassing example
for all the things possible with Scala.js. Before going through this tutorial, it would be helpful if you already know
the basics of Scala.js and have read through the official [Scala.js tutorial](http://www.scala-js.org/doc/tutorial.html)
and the great e-book [Hands-on Scala.js](http://lihaoyi.github.io/hands-on-scala-js/#Hands-onScala.js) by 
[Li Haoyi (@lihaoyi)](https://github.com/lihaoyi).

# Documentation

Tutorial [documentation](https://ochrons.github.io/scalajs-spa-tutorial) is now presented as a GitBook.

日本語を話せますか？Scala.js is Big in Japan, so I'm looking for help to translate the tutorial documentation into Japanese.
Contact me on twitter (@ochrons) or via email (otto@chrons.me) if you're interested! お願いします!

# Scala IDE users

If you are using Scala IDE, you need to set additional settings to get your Eclipse project exported from SBT.

```
set EclipseKeys.skipParents in ThisBuild := false
eclipse
```
