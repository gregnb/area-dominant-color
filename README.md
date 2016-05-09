# Javascript - Grab Dominant color of a supplied area

Simple function that returns a sorted palette of colors by occurance in a supplied area.

var image = document.getElementById('image')

var palette = areaPalette(image, {
	w: 200,
	h: 100,
	x: '50%',
	y: '70%',
	palettesize: 5,
	debug: false
});

var dominantColor = palette[0].hex;		
var constrastDom  = palette[0].constrast;
