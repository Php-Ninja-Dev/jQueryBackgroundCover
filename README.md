# jQuery Background Cover
jQuery plugin to adjust background image. background:cover doesn't maintain the image's center. 

## Author
Beto Ayesa for https://www.phpninja.info


## How to use?
1- Include jQuery 
2- Include the main js file (jQuery-backgroundCover.js) 
3- Have a DIV or html dom element where you want to apply the background, in this case, a div with id = background 

	$('#background').smartBackgroundResize({
		image: 'http://www.cinecritic.biz/es/images/stories/up-pixar/up3.jpg' 
		// relative or absolute path to background image file				
	});
