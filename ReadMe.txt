program to generate 3-second video of animated text (based on opencv)
(later I will push the source code)

run command 
	run.bat
or 
	animated input_string input.img font_color font_size img_zoom text_zoom out.avi

INPUTS (6 parameters):
  ~ text string, max 50 characters (e.g., "Hello World")
  ~ filename of background image (e.g., "background1.jpg")
  ~ color of text  (e.g., #FFFFFF)
  ~ font size of text (pt, e.g, 64)
  ~ zoom of background (decimal, e.g., 1.10)
  ~ zoom of text (decimal, e.g., 1.20)

OUTPUT: 
The text is centered on the screen, above the background image. 
Over the course of 3 seconds (30 fps, so 90 frames), the text will zoom in from the initial size, to the zoom amount (e.g., 1.20x), and the background will also zoom. 