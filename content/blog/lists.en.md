+++
title = "I need lists"
date = "2015-09-17T13:47:08+02:00"
description = "This is meta description for blog page"
tags = ["go"]
categories = ["programming"]
+++

Hugo uses the excellent [go][] [html/template][gohtmltemplate] library for
its template engine. It is an extremely lightweight engine that provides a very
small amount of logic. In our experience that it is just the right amount of
logic to be able to create a good static website. If you have used other
template systems from different languages or frameworks you will find a lot of
similarities in go templates.

This document is a brief primer on using go templates. The [go docs][gohtmltemplate]
provide more details.

## We need lists in Hugo:

<ul>
  <li>Bulletpoint 1
  </li>
  <li>Bulletpoint 2
  </li>
</ul>





[go]: <http://golang.org/>
[gohtmltemplate]: <http://golang.org/pkg/html/template/>
