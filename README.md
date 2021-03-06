# Lasercut Badge Generator

## Description
A Processing program that generate a set of stencil lasercut badges taking names from a .csv file. Originally developed for the Open Knowledge Festival 2012.

## How to use it
Open the sketch, and change the variable for the hashtag of your conference on line 61.
Create a names.csv file with name,surname,role in the event of each participant and save it into the sketch folder. Run the processing script, and it will generate a badges.pdf multipage file with resolution 900x600 px (px, not mm!).

Open the badges.pdf in your favorite vector drawing program (for example: [Inkscape](http://www.inkscape.org)), scale the drawing to 900x600 mm, that is by 283%. Now it will have the dimension of the full plate of the laser cutter.
<img src="https://raw.github.com/openp2pdesign/Lasercut-Badge-Generator/master/images/03.png">

Change the visualization to Outline, it will help you in understanding the drawing better.
<img src="https://raw.github.com/openp2pdesign/Lasercut-Badge-Generator/master/images/01.png">

Ungroup the whole drawing several times, until you see the letters separated. Then select them all and join them with the Union command: they are now ready for being used as a path for the laser cutter.
<img src="https://raw.github.com/openp2pdesign/Lasercut-Badge-Generator/master/images/02.png">

Cut your badges and glue a pin on them, you are ready!
<img src="https://raw.github.com/openp2pdesign/Lasercut-Badge-Generator/master/images/04.png">


## License
Realeased under [GPL v.3 license](http://www.gnu.org/copyleft/gpl.html)

<a href="http://mediafactory.aalto.fi/" style=" border-color:transparent!important;text-decoration:none!important;"><img src="http://mediafactory.aalto.fi/wp-content/uploads/2011/03/withlove_harm.gif" alt="With love from Aalto Media Factory" style="border-color:transparent!important;width:180px!important;height:50px!important;" /></a>