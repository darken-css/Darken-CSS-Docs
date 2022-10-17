---
title: Getting started
---

# Getting started guide
If you're new and want to include Darken CSS in your project, here's a guide to it.

## Installing on your website
The first step is well to install Darken CSS. To download a copy, [click here](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/darken-css/Darken-CSS/blob/main/main.css).

Then, extract the `.zip` file. On Windows, you can use the "Extract All..." tool from the right click menu, on Mac, you cannot really "extract" it, but you can drag it out.

Linux has many distributions, so here is some distribution-specific instructions:

- Ubuntu
  - Use a third party tool called `unzip`.
  - So use command: `sudo apt-get install unzip` to install.
  - Then, use `unzip main.css.zip`.
- Debian
  - Right click, choose "Extract Here...".
  - You can also use "Extract to..." to choose the destination directory.
- For more, go on Google and search.

Then, include this tag at the `head` element of your website:

```html
<link rel="stylesheet" href="/where-you-put-darken-css/main.css">
```

`/where-you-put-darken-css` defines where Darken CSS has been downloaded on. You need to change this to where you put it. An example is `/static/css`.
