---
title: Ultra Light Box
layout: default
---

# What is it

Ultra Light Box is a lightweight pure JavaScript image gallery inspired by [Lightbox](http://lokeshdhakar.com/projects/lightbox2/).

It has no dependencies.

## Supported browsers

* IE8+
* Any modern browser like Chrome, Firefox, Safari, Opera


## Usage

* Include the `ultralb.js` file in your html.

{% highlight html %}
<script type="text/javascript" src="ultralb.js"></script>
{% endhighlight %}

* Add images to a container with the class `.ultralb`

{% highlight html %}
<div class="ultralb">
	<img src="image1.jpg" alt="My Image" />
	<img src="image2.jpg" alt="My Second Image" />
	<img src="image3.jpg" />
</div>
{% endhighlight %}

Multiple containers with the class `.ultralb` can be added, each represent a gallery group.

The `alt` attribute of the image will serve as a title in the gallery.

## Demo

<div class="ultralb">
	<img src="images/image1.jpg" alt="Image 1"/>
	<img src="images/image2.jpg" alt="Second image"/>
	<img src="images/image3.jpg"/>
</div>
