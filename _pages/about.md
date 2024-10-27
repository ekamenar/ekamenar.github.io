---
layout: about
title: Home
permalink: /
#subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

#profile:
#  align: right
#  image: about/SciRo.jpg
#  image_circular: false # crops the image to make it circular
#  more_info: >
#    <p>Vukovarska 58,</p>
#    <p>51000 Rijeka</p>
#    <p>Croatia</p>

news: true # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

#include for swiper
images:
  compare: true
  slider: true
---

<swiper-container class="mySwiper" pagination="true" pagination-clickable="true" navigation="true" space-between="30" centered-slides="true" autoplay-delay="2500" autoplay-disable-on-interaction="false">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/about/about.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/about/about1.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/about/about2.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/about/about3.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/about/about4.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>

Our research group focuses on investigations in the fields of mechatronics, robotics, machine learning, and AI. We leverage Koopman operator theory to model and control dynamical systems, such as soft robots exploited in rehabilitation robotics.

<!--Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.-->
