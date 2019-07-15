---
title: "All new codemute blog"
categories:
  - intro
tags:
  - blog
author: Abhinav Kaushlya
---

Hey everyone, welcome to codemute blog. Here you can introduce yourselves, let
the world know about you. You can also share your experiences, your projects
or something you'd like to let people know. :smile:

Please be free to add new posts, we will be more than happy to get them here.
All you need to do is create a new post in the `_posts` folder of site's
[github repository][github].

This is the step by step guide to get you started:

1. Fork the [site repository][github].

2. Clone your fork:
```
git clone https://github.com/<YOUR-GITHUB-USERNAME>/codemute.github.io
```

3. Change directory and Checkout a new branch:
```
cd codemute.github.io
git checkout -b some_branch_name
```

4. Add your post to the `_posts` directory with the file name in the format
`YEAR-MM-DD-your-post-name.md`.

5. Add YAML front matter, you can add images, links, buttons, etc. Have a look
at the [sample posts][sample-posts] to get started.

6. Once you're satisfied with your changes, commit them and push:
```
git add .
git commit -m "My new post"
git push origin some_branch_name
```
7. Now you can visit your fork on Github and create a Pull Request. We will
review it and will get it merged as soon as possible. :tada:

Sound's simple, so get started. In case if you need help, feel free to ask
on out [gitter channel][gitter].

[sample-posts]: https://github.com/mmistakes/minimal-mistakes/tree/master/docs/_posts
[gitter]: https://gitter.com/codemute
[github]: https://github.com/codemute/codemute.github.io
