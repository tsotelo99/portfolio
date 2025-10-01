---
title: Header Examples
layout: base
date: 2024-10-24
header-image: /assets/images/backgrounds/pano-1.jpg 
---

# Header Examples
This page shows various ways you can use header images on your pages. The blue code boxes show what code you can copy and paste on to your page, and the result shows up just underneath it. 


## Page header
It's common to include a large image at the top of the page. In the YML header at the top of the page, include something like `header-image: images/image_name.jpg`. The YML header for this page is:

```
---
title: Image Examples
layout: base
date: 2025-09-13
header-image: /assets/images/backgrounds/pano-1.jpg 
---
```


## Section Header Images
The [images page](images) shows how to create jumbotron images on your page that span the whole browser window. You can also use jumpbotrons as a section divider. Optionally, you also can add a title and subtitle.

```
{% raw %}
{% include jumbotron.html
  height="30vh"
  image-path="/assets/images/backgrounds/pano-1.jpg"
  title="Section Heading"
  subtitle="Your subtitle goes here"
%}
{% endraw %}
```


{% include jumbotron.html
  height="30vh"
  image-path="/assets/images/backgrounds/pano-1.jpg"
  title="Section Heading"
  subtitle="Your subtitle goes here"
%}


##  Peekaboo Headers
You can see that the section header above is basically embedded on the scrolling page. This means it keeps its relative position to the text and scrolls up and down with everything else. We can create the effect of the header revealing parts of a larger image behind it as the page scrolls up. This is what's happening as you scroll now:

```
{% raw %}
{% include scrollybox/bg.html
  height="40vh"
  image-path="/assets/images/backgrounds/pano-1.jpg"
%}
{% endraw %}
```

{% include scrollybox/bg.html
  height="40vh"
  image-path="/assets/images/backgrounds/pano-1.jpg"
%}



## That's a wrap 
That's all for basic headers. 
