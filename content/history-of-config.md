+++
title = "A Dive into Configuration"
date = 2019-11-28
description = "A look at where configuration in software has come from and where it's going"
+++

Configuration files are all around us. A casual look into a basic web app will show a shocking number of files that are not code at all (CSS, Gruntfile, Dockerfile, .gitignore just to name a few).

Building almost any non-trivial application requires not just knowledge of a programming language, but many configuration languages for defining how it builds and how it runs.

But why is there so much configuring going on in the first place? Is it necessary? To answer, we'll need to step back and first understand the problems that configuration solves, how it came to dominate the world of computing, and finally how it can be most effectively used in our toolbox.

## Config is not new

If we look back into the history of computing and try to pinpoint when exactly the idea of configuration arose, we find it even in the earliest days. 

The famous Enigma machine 