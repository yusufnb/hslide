# jQuery Horizontal Slider Plugin

## Usage 
```javascript
$('#slide').hslide( options )
```

## Options
delay         - the interval of slideshow
speed         - the duration of sliding animation

## Example:
```
	<body>
	<style>
		#slider {width: 450px; height: 250px; padding:0; border:0;}
		#slider img {padding: 0; margin:0; border:0;}
		#slider .clicker a {width: 11px; height: 11px; background: #fff; margin-right: 2px;}
		#slider .clicker a.active {background: #ff0;}
	</style>

	<script src="http://code.jquery.com/jquery-1.5.2.min.js"></script> 
	<script src="jquery.hslide.js"></script> 
	<script>
		$(function(){
			$('#slider').hslide();
		});
	</script>

	<div id="slider">
		<div><img src="http://placehold.it/450x250&text=1"></img></div>
		<div><img src="http://placehold.it/450x250&text=2"></img></div>
		<div><img src="http://placehold.it/450x250&text=3"></img></div>
		<div><img src="http://placehold.it/450x250&text=4"></img></div>
		<div><img src="http://placehold.it/450x250&text=5"></img></div>
	</div>
	</body>

```

## License

This plugin is dual-licensed under the GNU General Public License and the MIT License and
is copyright 2011 Yusuf Najmuddin yusufnb@gmail.com
