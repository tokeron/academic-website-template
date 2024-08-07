---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<style>
  .content {
    max-width: 100%; /* Adjust this value to increase or decrease text width */
    margin: auto;
  }
</style>

<!-- I'm Michael Toker, a PhD candidate and NLP researcher in the computer science faculty at the Technion. I'm fascinated by how LLMs encode information and how to make llms more explainable and robust. If you share my curiosity, explore my projects and feel free to reach out with any questions or comments. -->

<!-- ### Welcome!

Hello and welcome to my webpage! I’m Michael Toker, a PhD candidate and a passionate researcher in the field of natural language processing. On this webpage, you can find out more about me, my work, and my interests. I’m fascinated by how language models encode information and how we can make them more explainable and robust. If you share my curiosity and enthusiasm, I invite you to read on and explore my projects. You can also reach out to me anytime if you have any questions or comments. Thank you for visiting and enjoy! -->

<div class="container">
<div class="row">
<center>
<!-- <img src="{{ site.url }}{{ site.baseurl }}/images/banner.jpg" width="100%"/><br/> -->
<!-- Examples of Feynman diagrams. <br/> -->
<!-- Feynman R., The theory of positrons. <i>Phys. Rev.</i> (1949) -->
</center>
</div>
</div>
<br/>

### About me

I’m Michael Toker, a PhD student at the Technion's Computer Science faculty, part of the NLP research group under Prof. Yonatan Belinkov. My research focuses on the explainability and robustness of language models. I aim to understand how these models encode information and how to make them more reliable. My recent work focuses on text-to-image (T2I) models and the role of the text encoder in these models. We published a paper in the ACL 2024 main conference, proposing a new method called 'Diffusion Lens,' which aims to interpret T2I models by generating images from their intermediate calculations. Currently, I am working on understanding how information flows in the text encoder in T2I models and on extending our method to apply to any large language models (LLMs) and vision-language models (VLMs).

<!-- In my last work, titled “Diffusion Lens”, I developed a method to generate images from intermediate representations of the language model. Using this method, I found that the text encoder gradually builds prompt representations across multiple scenarios. This work is part of a series of projects that aim to shed light on the inner workings of language models. You can find my publications, code, and images on this webpage. Feel free to contact me if you have any questions or comments. -->

<br/>

# Recent Talks

## A journey from text to image - NLP IL - Vision-Language Club #1

<!-- Youtube video -->
<section class="hero is-small is-light">
  <div class="hero-body">
    <div class="container">
      <!-- Paper video. -->
      <h2 class="title is-3 has-text-centered">Video Presentation</h2>
      <div class="columns is-centered">
        <div class="column is-four-fifths">
          <div class="publication-video">
            <!-- Youtube embed code here -->
            <iframe src="https://www.youtube.com/embed/8qEeumJL_FM" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- End youtube video -->

<!-- Youtube video -->
<section class="hero is-small is-light">
  <div class="hero-body">
    <div class="container">
      <!-- Paper video. -->
      <h2 class="title is-3 has-text-centered">Video Presentation</h2>
      <div class="columns is-centered">
        <div class="column is-four-fifths">
          <div class="publication-video">
            <!-- Youtube embed code here -->
            <iframe src="https://www.youtube.com/embed/hAZr8pjyt-Y?start=506" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- End youtube video -->

### Publications

{% bibliography --query @inproceedings %}
{% bibliography --query @article %}
