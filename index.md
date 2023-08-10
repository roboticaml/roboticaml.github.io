---
layout: home
title: "Sign language at scale: Robotica"
---
# Sign Language at Scale

**Extend your reach to 150,000 additional customers in the UK**
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
        src="https://cdn.api.video/vod/vi65dmFVVfCcNEfBZddTzGJh/mp4/1080/source.mp4"
        type="video/mp4"
        aria-labelledby="title"
        aria-describedby="transcript"
      >
      <iframe src="https://embed.api.video/vod/vi65dmFVVfCcNEfBZddTzGJh" width="100%" frameborder="0" scrolling="no" allowfullscreen="true">
      </iframe>
    </video>
  </figure>
</div>

<br />

<h2>Did you know...?</h2>
{%- include faq.html %}

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

When your content is designed with accessibility in mind, it becomes a powerful tool that resonates with a broader spectrum of individuals. Not only does it ensure your message reaches people with diverse abilities, but it also has the potential to transcend time, remaining relevant and impactful for longer periods. By making your content accessible, you unlock the door to a wider audience, fostering inclusivity and maximizing the lasting impact of your communication efforts.

Embracing accessible content amplifies the concept of the "long tail" effect, where your content's cumulative value extends far beyond its initial release. By making your material accessible to individuals who may have previously been excluded, you create a ripple effect of engagement and sharing. This extends the lifespan of your content, ensuring it continues to resonate and deliver value over time. As your accessible content gains traction, it contributes to a lasting legacy, building a stronger connection with your audience and establishing your organisation as a champion of inclusivity and innovation.