---
location: homepage
head:
  title: Embed Video and Audio
  subtitle: null
style:
  id: video
  class: bgclear
  media:
    img:
      url_path: /img/backgrounds/cream_pixels.png
      pattern: true
      parallax: false
      overlay: null
      blur: false
  tint_color: 'rgba(163,166,152,0.3)'
cta:
  headline: null
  btnText: null
  btnType: null
  btnLink: null
  subtext: null

---

### Add Responsive Videos from YouTube or Vimeo

{% include widgets/embed-video.html youtube="womIxQqO2tE" responsive="16by9"  %}
<em>Video copyright Charity Water</em>
&nbsp;

Easily embed responsive 4x3 or 16x9 from YouTube or Vimeo with a customizable short code:

`{% raw %}{% include widgets/embed-video.html youtube="XEne36YxyKI" responsive="16by9"  %}{% endraw %}`


&nbsp;

### Embed Audio Tracks from Soundcloud

{% include widgets/embed-audio.html soundcloud="https://soundcloud.com/sugar-hill-records/sam-bush-sailin-shoes" %}

&nbsp;

Or, use the 'audio embed' widget to include music or podcast embeds from soundcloud:

`{% raw %}{% include widgets/embed-audio.html soundcloud="https://soundcloud.com/sugar-hill-records/sam-bush-sailin-shoes" %}{% endraw %}`

Learn how to use and [customize this template](/about/).
