---
# This is a full listing of available Frontmatter options, available for any content (.md) file.
title: DH Alchemy
layout: page
excerpt: # used for page excerpts and META (will be overwritten if SEO used below)
author: the associates # only displayed on Post lists and detail views. Defaults to _data/meta.authorURL
eleventyNavigation: # Required if want to display in Main Nav Bar
  key: main # "main" is required
  title: Welcome # as it will appear in the nav
  order: 1 # order to display in the nav (index = 1)
seo: # SEO values are used for OG and will overwrite 'title' and 'excerpt' above
  title:
  description:
  image: # used for OG:image and Twitter:image. Overrides default set in _data/meta.siteImage
hero: graphic # options: carousel, graphic, video, split (text & image)
heroSettings:
  height:
    mobile: # options = h-1/1 (default = full screen), h-1/2, h-1/3, h-3/4, h-9/10, h-48 (12rem, 192px), h-56 (14rem, 224px), h-64 (16rem, 256px)
    desktop: # leave blank to inherit "mobile" height (default = full screen)
  bg:
    color: # default bg-black
    image: home/default.png # relative to /assets/images/
    imagePosition: # options = bg-center (default), bg-left, bg-right
    video: pixabay-john-macdougall.mp4 # local relative /assets/video/, or full https://... if remote?
    opacityMobile: opacity-50 # options opacity-n, 5, 10, 15, 20, 25, 50, 75, 100 (default)
    opacityDesktop: opacity-75 # Leave blank to inherit opacityMobile, use same options as opacityMobile
  headingText: DH Alchemy<br><i>turning data into wisdom</i>
  headingTextColor: # default = text-white (can use any TailwindCSS text-[color]-[xxx])
  headingTextCase: # default = as typed - options: uppercase, lowercase, capitalize
  subheadingText: A digital humanities consultancy
  subheadingTextColor: # Leave empty to inherit headingTextColor or default (text-white) or use any text-[color]-[xxx]
  buttonText:  # no button generated if left blank
  buttonURL:  # full url required. Example: https://thisdomain.com/somepage/
  buttonTextColor: # leave blank to inherit from /src/_data/colors.buttonCustom or buttonDefault
  buttonBgColor: # leave blank to inherit from /src/_data/colors.buttonCustom.bg or buttonDefault.bg
  buttonBgHover: # leave blank to inherit from /src/_data/colors.buttonCustom.bgHover or buttonDefault.bgHover
  buttonBorder: # leave blank to inherit from /src/_data/colors.buttonCustom.border or buttonDefault.border
  carousel:
    images:
      - home/6.jpg
      - home/7.jpg
      - home/8.jpg
      - home/9.jpg
---

# A Digital Humanities Consultancy

You've got lots of data, lots of information, tonnes of documents. How do you make sense of it all? Is this where you buy some 'ai'-powered solution off the shelf? Do you make your own solution? What should you do? Worried about being left behind?

Let us offer advice, guidance, and support for implementing humanistic and humane approaches to your data and your workflows. We're the people who will tell you when something might not be a good idea.

On the other hand, if it _is_ a good idea, we can take it and make it _better_.

Drop us a line at dhalchemy at craftingdigitalhistory dot ca.

[About](/about)  |  [Contact](/contact)

