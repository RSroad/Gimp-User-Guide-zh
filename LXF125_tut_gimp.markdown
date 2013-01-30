Tutorial Gimp Open source image-editing
Gimp
software you can get your teeth into
Gimp: Sin City
Artist and developer Michael J Hammel goes all Frank Miller in this month’s
rainy, grainy Gimp graphics tutorial. One day a real rain’s gonna come...
Before
After
A
Our
expert
Michael J
Hammel
is a contributor to
the Gimp project
and the author of
three books on the
subject, including
his latest, The
Artist’s Guide to
Gimp Effects.
s a child I never spent much time with Marvel or
DC Comics in my pocket, preferring instead to idle
away my hours with images of Star Trek and
moonshots, parked on the front porch with Arthur C Clarke
and Isaac Asimov, reaching for the stars with Carl Sagan and
hiding under the sheets to listen to Dr. Dimento on the radio. I
was a weird kid, even by comic book reader standards. But
I’ve grown up since then, and as my wife says I’m far more
personable than your average geek. I read less, watch movies
more, and perform a reasonable bass on Guitar Hero. And I’m
still not into comics.
Despite this it is nearly impossible, even for grown but still
demented geeks such as myself, to have completely avoided
the impact that comics and their darker, brethren Graphic
Novels, now have on society. Constantly reaching for ever
more bizarre ways to bloody the cast, movie producers have
turned to comics for story concepts, most notably to
Project resources
Stock photos:
Man with Gun www.bigstockphoto.com/photo/view/2123798
Men with Gun (Red Tie) www.bigstockphoto.com/photo/view/3343608
Handgun www.bigstockphoto.com/photo/view/2944267
Building www.morguefile.com/archive/?display=55516
translate the theme of the comic world on to the big screen.
Ignoring the hideous adventures that were Roger Rabbit and
Spawn, Hollywood seems to have found its comic groove and
is happily embedded in the world of super heros.
Hats off to the heroes
So it is that this geek must pay homage to the genre. Recent
hits such as Iron Man and The Dark Knight have added a
slightly darker tone to the circa 1970s incarnations of of
Superman and Wonder Woman. Sin City and Watchmen took
this new vision to even darker realms. Fortunately for this
Gimp fan, Sin City left a reasonable graphic mark upon me
with its high contrast and splashes of colour. Which leads to
this issue’s tutorial...
This month we’ll use multiple stock photos to show our
rugged hero patrolling the bad lands of the city under a rain
soaked and miserable night. The whole thing will be black and
white with just a single splash of colour. What’s fun about
working in black and white is that the image is more likely to
fit into the gamut of the local ink jet printer. I’ll address the
one place this might not be the case when we get to the
touch of colour.
Last month We chilled out with a peace, love and understanding montage.
82 LXF125 December 2009
LXF125.tut_gimp 82
www.linuxformat.com
28/9/09 4:39:24 pm
Gimp Tutorial
style
Step by step: Create a gritty noir look
1
Base image
The base image provides our main character, a
tough guy with a gun on a solid, light-coloured
background, with a resolution of 1600x1067
pixels. Desaturate the image (Colours >
Desaturate), then choose the Lightness option,
which will let you keep a high contrast between
his face and the background.
4
First rain: drops
Open the Motion Blur filter (Filters > Blur >
Motion Blur) and set the Blur Type to Linear,
the Length to 120 pixels and the Angle to 90
degrees. Click on OK to apply the blur to the
noise in the Rain 1 layer. Scale the Rain 1 layer
(Layer > Scale) by 140%. This is done by
changing the Scale Units menu in the Scale
Layer dialog to Percent and typing 140 in the
Width field. The Height field will automatically
adjust to maintain the width-to-height ratio
when you press the Scale button.
2
Increase contrast
Open the Levels dialog (Colours > Levels), then
click on the white-point eye dropper (on the
right-hand side beneath the Levels histogram)
and click in the upper-right background of the
image. This will make the background
completely white, with the white-point slider
moving to just left of centre of the histogram.
Move the black point slider to the right until it is
very near the white point. The result will be a
nearly completely black and white image.
5
First rain: shear
Zoom out to see the layer boundary for the Rain
1 layer, then choose the Shear transformation
tool from the Toolbox. Click in the image and
drag until the edges of the layer in the shear
preview touch the top-right and bottom-left
corners of the image window before clicking on
the Shear button in the Shear dialog to apply
the transformation. Open the Levels dialog and
adjust the white point to around 107 and the
black point to around 116. Reset the layer to fit
the image (Layer > Layer to Image Size).
3
First rain: noise
Add a transparent layer (Layer > New). Name
this layer Rain 1. Open the Hurl filter (Filters >
Noise > Hurl). The default settings are
sufficient here: Random Seed = 10,
Randomisation % = 50, Repeat = 1. Click OK to
render the noise in the Rain 1 layer. The noise
will be coloured, so desaturate it. (While we’ve
chosen the Lightness option here, any of the
desaturation options will work.)
6
Second rain
Add a second layer of rain, using the same
process as the first layer of rain but with less
shear applied so the rain falls more vertically.
The Levels adjustment may also be slightly
different, again according to taste. Later,
because of the contrast changes brought on
by adding in background elements, the two
rain layers modes and opacity may need to be
adjusted. Be sure to name the second rain
layer Rain 2.
If you missed last issue Call 0870 837 4773 or +44 1858 438795.
www.tuxradar.com
LXF125.tut_gimp 83
December 2009 LXF125 83
28/9/09 4:39:27 pm
Tutorial Gimp
7
Mask the base image
8
Click on the base image layer to make it the active layer. Add an alpha
channel and a white layer mask to the layer, then re-open the original
image. Choose the Fuzzy Select tool, set the Threshold to 70 and
Shift+click to select the blue areas. Paste this selection into the mask of
the base image layer. Use the Levels dialog to set the black point to 254.
9
Fix the rain layers
10
In the Layers dialog, reduce the opacity level for each Rain layer to
30%, then merge the two layers (click on the Rain 1 layer and do Layer
> Merge Down). Adjust the contrast of the merged layer using the
Brightness-Contrast dialog (Colours > Brightness-Contrast) and set
the Brightness slider to -121 and the Contrast slider to 127.
11
Put the tie on
Add a splash of colour
Open the image of the gangster with a red tie. Choose the Fuzzy Select
tool and set the Threshold to 95. Click anywhere on the red tie. If there
are spots of unselected tie inside the selection, grow the selection by a
pixel to pick them up. The inset image shows the selection with Quick
Mask enabled and the mask colour set to green. Copy the selection.
12
Paste the selection into the base image, it horizontally then desaturate
the layer and choose a new red colour. Set the Lock Transparency
button in the Layers dialog. Choose the Bucket Fill tool set the Mode to
Grain Merge and the Affected Area to Fill Whole Selection. Click in the
Red Tie layer to recolour the image.
Background Building
Scale the image of the background building to fit the size of the base
image layer, then paste it into the base image and drag the new layer to
the bottom of the layer stack. Turn the visibility of all other layers off to
make these next steps easier, then desaturate and adjust the contrast
of the image just as we did in step 2.
Update the building
Open the scale dialog (Layer > Scale). Click on the chain link to break it
in order to change the aspect ratio of the layer. Scale the Building layer
by 165% wide and 140% high. Use the Move tool to drag the layer to
the left until the front entrance is to the left of the gun. Reset the layer
size to match the image size (Layer > Layer to Image Size).
Never miss another issue Subscribe to the #1 source for Linux on p102.
84 LXF125 December 2009
LXF125.tut_gimp 84
www.linuxformat.com
28/9/09 4:39:28 pm
Gimp Tutorial
13
Lampposts guideline
14
Add a transparent layer just above the Building layer. Set the
foreground colour to a medium grey (HTML notation cbcbcb). Draw a
line from left to right at roughly the height of the top of the first floor of
the building. Later, this layer will be removed.
15
Lamps
16
Create an oval selection in a new layer, then cut out the bottom half of
the selection. Position the selection over the left lamp post. Choose the
Blend tool and drag a linear gradient from black to grey starting at the
top of the selection down to the straight edge. Repeat for the other
lamppost, then clear the selection (Select > None).
17
Adjust the lampposts
Lamp lights
Create a transparent layer beneath the Lamps layer in the Layers
dialog. Use the Paths tool to outline a box below the left lamp, then
convert the path to a selection. In the selection, apply a white-to-
transparent gradient from the top to the bottom, and repeat for the
other lamp. Clear the selection.
18
Open the Gaussian Blur filter (Filters > Blur > Gaussian Blur) and apply
a 10-pixel blur in both the X and Y directions to the Lights layer. Set the
layer Opacity to between 35 and 40%. At this point you can delete the
guideline layer, or simply turn off its visibility in the Layers dialog.
Draw the lampposts
Add a transparent layer above the Guideline layer, and with a small-
radius paintbrush draw a line on the left of the front entrance of the
building from the guideline down to the bottom of the building. Repeat
the process for the right side of the entrance. Duplicate this layer and
offset it by 1 pixel in the X direction. Reduce the Brightness to -127.
Final effect
To darken the background, add a transparent layer just above the
Building layer. Fill this layer with black, add a layer mask and choose
the Blend tool. Configure a Radial shape that runs from Black to grey,
then click in the middle of the man’s face and drag toward the index
finger on the gun to draw the radial, black-to-grey mask. LXF
Next month We’ll add polish to your desktop with some OS X-like icons.
www.tuxradar.com
LXF125.tut_gimp 85
December 2009 LXF125 85
28/9/09 4:39:30 pm

