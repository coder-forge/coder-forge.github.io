---
layout: post
title: "Learn - Required Software"
description: ""
category:
tags: []
---
{% include JB/setup %}

<a href="/2016/05/07/required-software">Required Software</a>
<a href="/learn"> Slide - cheatsheet</a>

### Getting it all installed

We've noticed that sometimes it can be frustrating for people new to computers
to get everything installed, databases, language parsers, IDE's - before you
know it you've a mess of 'hello world' apps and no idea where most of them are!

To help solve this issue we have decided that [Docker](https://www.docker.com/). This basically containerises a machine with all required software on your computer. You can then start and stop the container as needed.

Once [Docker](https://www.docker.com/) is installed then we only have to provide a `Dockerfile`, which is a text file with the software requirements. This file will then download and install what is needed in a nice little container.

You can access our [Docker account here](https://hub.docker.com/r/coderforge/). Please comment below if you have questions or get stuck.
