---
layout: home
title: "Sign language at scale: Robotica"
---
# Sign Language at Scale
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
      <iframe src="https://embed.api.video/vod/vi2Nn14OjKAv5QRLMc1wSSad" width="10%" height="100%" frameborder="0" scrolling="no" allowfullscreen="true">
      </iframe>
    </video>
  </figure>
</div>
Extend the reach and value of your content with British Sign Language translations

<br />
## Did you know...?

<div class = 'faq'>
    {%- for item in site.data.faq %}
      <p> {{ item.faq }}</p>
    {%- endfor %}
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
