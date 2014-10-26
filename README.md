Ultra Light Box
===============

# What is it

Ultra Light Box is a lightweight pure JavaScript image gallery inspired by [Lightbox](http://lokeshdhakar.com/projects/lightbox2/).

It has no dependencies.


## Supported browsers

* IE8+
* Any modern browser like Chrome, Firefox, Safari, Opera


## Usage

* Include the `ultralb.js` file in your html.

```html
<script type="text/javascript" src="ultralb.js"></script>
```

* Add images to a container with the class `.ultralb`

```html
<div class="ultralb">
	<img src="image1.jpg" alt="My Image" />
	<img src="image2.jpg" alt="My Second Image" />
	<img src="image3.jpg" />
</div>
```

Multiple containers with the class `.ultralb` can be added, each represent a gallery group.

The `alt` attribute of the image will serve as a title in the gallery.

## [Demo](http://kcsoft.github.io/ultralb/)