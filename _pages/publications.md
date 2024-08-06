<!-- ---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
</div>

<div class="jumbotron">
### Publications
{% bibliography --query @inproceedings %}
{% bibliography --query @article %}
</div> -->

---

title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]

---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
.publication-container {
    margin-top: 20px;
}
.publication-container img {
    width: 100%;
    height: auto;
}
.publication-details {
    margin-top: 10px;
}
</style>

<div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
</div>

<div class="jumbotron">
### Publications
{% bibliography --query @inproceedings %}
{% bibliography --query @article %}
</div>

<div class="jumbotron">
### Selected Publications
<p>* indicates equal contribution.</p>
<div class="columns publication-container">
  <div class="column is-one-third">
    <img src="static/videos/astronaut_dog_sd3.gif" alt="Astronaut Dog">
  </div>
  <div class="column is-two-thirds">
    <p><strong>Diffusion Lens with Stable Diffusion 3: Images generated from different intermediate layers of the text encoder using our method, Diffusion Lens.</strong></p>
    <p>
      Michael Toker<sup>*</sup>, <a href="https://orgadhadas.github.io/" target="_blank">Hadas Orgad</a><sup>*</sup>, <a href="https://venturamor.github.io/" target="_blank">Mor Ventura</a><sup>*</sup>, <a href="https://www.linkedin.com/in/dana-arad/" target="_blank">Dana Arad</a>, <a href="https://belinkov.com/" target="_blank">Yonatan Belinkov</a>
    </p>
    <p><em>arXiv, 2024</em></p>
    <p><a href="https://arxiv.org/abs/2403.05846" target="_blank">arXiv</a></p>
  </div>
</div>
</div>
