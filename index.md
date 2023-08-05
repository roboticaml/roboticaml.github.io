---
layout: home
title: "Sign language at scale: Robotica"
---
# Sign Language at Scale

Extend your reach and value:
AI Sign Language translations make your content accessible to and additional 150,000 customers.

<div class="container">
  <figure id="videoContainer" data-fullscreen="false">
    <video 
      volume="0.0"
      width="100%"
      id="video"
      preload="auto"
      disablePictureInPicture
      controlslist="nodownload"
      autoplay
      muted
      loop
    >
      <source
        src="https://cdn.api.video/vod/vi2Nn14OjKAv5QRLMc1wSSad/mp4/1080/source.mp4"
        type="video/mp4"
        aria-labelledby="title"
        aria-describedby="transcript"
      >
      <iframe src="https://embed.api.video/vod/vi2Nn14OjKAv5QRLMc1wSSad" width="100%" frameborder="0" scrolling="no" allowfullscreen="true">
      </iframe>
    </video>
  </figure>
</div>

<br />

<!-- Make these show one at a time:
       displays for a few seconds then either scrolls up to be replaced
       or the next FAQ fades in or something to replace it. -->

  <h2>Did you know...?</h2>
  <div id="faqCarousel" class="carousel slide carousel-fade" data-ride="carousel" data-interval="1000">
    <ol class="carousel-indicators">
{%- for item in site.data.faq %}
<li data-target="#faqCarousel" data-slide-to="{{ item.index }}" {% if item.index== 0 %} class="active"{% endif %}></li>
{%- endfor %}
  </ol>
    <!-- Wrapper for slides -->
    <div class="carousel-inner">

{%- for item in site.data.faq %}
      <div class="carousel-item{% if item.index== 0 %} active{% endif %}">
        <img src="{{ item.image }}" alt="{{ item.alt }}" style="width:100%;">
        <div class="carousel-caption">
          <h3>{{ item.short }}</h3>
          <p>{{ item.long }}</p>
        </div>
      </div>
{%- endfor %}

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#faqCarousel" data-slide="prev" onclick="$('#faqCarousel').carousel('prev')">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#faqCarousel" data-slide="next" onclick="$('#faqCarousel').carousel('next')">
      <span cclass="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

<br />
## Sectors
<div class = 'services'>
  <div class = 'grid-3 wrap'>
    {%- for sector in site.data.sectors %}
    <a class = 'service center' {% if sector.link %} href='{{ sector.link }}'{% endif %}>
      <img src = '{{ sector.icon }}' class = 'service-icon' />
      <h4>{{ sector.name }}</h4>
      <h4>{{ sector.sectors }}</h4>
      {{ sector.description | markdownify }}
    </a>
    {%- endfor %}
  </div>
</div>

<br />

## We are trusted by the world’s leading companies and organisations. 
<br />

<div class = 'testimonials'>
  <div class = 'grid-3 wrap'>
    {%- for testimonial in site.data.testimonials %}
    <a class = 'service center' {% if testimonial.link %} href='{{ testimonial.link }}' target="_blank" {% endif %}>
      <img src = '{{ testimonial.logo }}' class = 'service-icon' alt='{{ testimonial.customer }}' />
      <h4>{{ testimonial.testimonial }}</h4>
      <h4>{{ testimonial.sectors }}</h4>
      {{ testimonial.quote | markdownify }}
    </a>
    {%- endfor %}
  </div>
</div>

![Young adults using sign language](/images/deaf-young-adults.png)

## Create an inclusive environment

Our platform supports your ambition to create a fully inclusive environment, where d/Deaf people are included and feel welcome. We can help you to maximise customer numbers, deepen and broaden engagement, and efficiently extend the value of your communications to increase ROI and profitability. Our accessibility products and services enable you to deliver equality and access of information and services to the d/Deaf community.

### Accessible content enables bigger audiences: your content goes further, lasts longer and finds a wider audience
