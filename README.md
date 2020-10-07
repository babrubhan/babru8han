This is an example one-pager site that prospective job-seekers can use to quickly
highlight their accomplishments and make an introduction. It can be hosted for free using
GitHub Pages (as a Jekyll page).

This is based on a heavily pared-down version Jerome Lachaud's [Freelancer Jekyll theme](https://github.com/jeromelachaud/freelancer-theme).
Jerome's original theme is well-suited for designers to easily assemble a portfolio site of their visual work; this
is a prose-centric version tailored to software developers. [formspree](http://formspree.io/) is used for the contact form.


## How to use
 - Place a image in `/img/portfolio/`
 - Replace `your-email@domain.com` in `_config.yml` with your email address. Refer to [formspree](http://formspree.io/) for more information.
 - Create posts to display your projects. Use the follow as an example:
```txt
---
layout: default
modal-id: 1
date: 2020-10-05
img: cabin.png
alt: image-alt
project-date: Oct 2020
client: The Client
category: Web Development
description: The description of the project

---
```

## Demo
View this jekyll theme in action [here](https://www.babrubhan.com)

---------
For more details, read the [documentation](http://jekyllrb.com/)
