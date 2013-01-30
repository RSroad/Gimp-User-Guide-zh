Tutorial Gimp Open source image-editing
Gimp
software you can get your teeth into
Gimp: Shattered
She’s breakin’ up, captain! Gimp author Michael J Hammel shows how to 
make someone’s face fragment and drift away in a few simple steps.
Our goal is to make a face look as though it’s breaking up
and drifting away in a cloud of squares.
T
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
his month’s tutorial is one I’ve thought about for
years, but never really understood how to do until
now. The concept is simple enough: snip pieces out of
a photo and make them look as if they’re floating away, as
though the original photo were slowly dissolving. The obvious
way to do this is with manual clippings. You select shapes
from the original, cut and copy them to a new layer, which you
then position slightly left or right of the original, and repeat.
Using differently sized selections, you can simulate the pieces
moving closer or further away. This is easy enough to explain,
but in practice, you end up needing hundreds of layers to get
the desired effect. There’s no reason it can’t be produced in
this way, but it’s much more work than you should have to do.
And managing countless layers, each for one small clipping,
will become a real pain.
My thinking on this problem has always focused on taking
bits of the original and moving them, but I was never able to
come up with a fast and easy way of doing it. The ideal
Project resources
This tutorial is based on PSDFan’s Shattered Face tutorial 
 psdfan.com/tutorials/designing/create-a-shattered-face-graphic
 Gimp Paint Studio code.google.com/p/gps-gimp-paint-studio
 Stock photo www.bigstockphoto.com/photo/view/1892998
process would involve nothing more than painting. Imagine
using the Clone tool for the clippings: at first glance, cloning
seems to be perfect. However, there are two problems with
this. The first is that cloning doesn’t remove the part of the
image from the original location; the second is that cloning
only copies the original to a new location, it doesn’t create
clippings that aren’t adjacent to each other. And the whole
point of the dissolve is to make it look like pieces of the
original are floating away from each other.
In my never-ending rummaging through internet tutorials,
I finally found a Photoshop walkthrough that explained the
real trick for this effect: duplicating the original layer and
scaling it in the direction that the pieces will float away. The
scaled layer is placed below the original, a black mask is
added to the scaled layer and a white mask to the original
one. Shapes are drawn in the masks, to cut from the original
or expose in the scaled layer. Brush Dynamics are used to
produce randomly sized shapes, so that the floating pieces
(or cuts from the original) can be created using simple brush
strokes or dabbing. In the end, only a single layer is required
for the floating pieces and another for the original, with the
dissolving bits clipped from it.
This month’s tutorial will expand on this process by adding
a few artistic features, but for the most part will focus on the
dissolving effect. I’ll be using the Gimp Paint Studio (GPS)
collection of presets and brushes for the artistic portion, but
this isn’t required for the dissolving effect. We’ll create a new
brush with the Brush Editor, prior to making the floating bits.
Last month we took a step into the wonderful world of desktop icons.
80     LXF127 January 2010
LXF127.tut_gimp 80
www.linuxformat.com
20/11/09 3:37:41 pm
 face
Step by step: Dissolve a face
1
Get the source image
The original 1064x1600 source image comes
from the www.bigstockphoto.com collection.
The photo was chosen for its high-contrast
background and limited hair around the face.
Both features will make it easier to select just
the face from the photo. In Gimp, create a new
image (File > New) that’s 1750x1600 pixels in
size. Open the source photo (File > Open) and
drag its only layer into the new image window.
Name the layer that this creates Source.
4
Desaturate the face
To avoid issues with out-of-gamut colours
when printing, desaturate the Source layer
(Colours > Desaturate). Use the Average
setting in the Desaturate dialog, because it
provides the best contrast in facial features,
such as the lips, nose and eyes. Over the
following two steps, we’ll enhance the face so
that it contrasts better with the backdrop that
we’ll create for the image later on.
2
Align source image
Add an Alpha Channel (Layer > Transparency
> Add Alpha Channel) to the Source layer.
Choose the Align tool from the Toolbox. Click
on the background layer in the image window
first, then hold down the Shift key and click on
the Source layer in the image window. In the
Tool Options dialog, set the Relative To option
to First Item, then click the Align Right Edge
button, followed by the Align Top Edge button.
5
Brightness and contrast
Duplicate the Source layer (Layer > Duplicate)
and name the new layer Brightness. Next,
open the Brightness/Contrast dialog (Colours
> Brightness-Contrast). Set the Brightness
slider to 30 and the Contrast to 70, then apply
these settings. Once you’ve done this, set the
Brightness layer mode to Multiply and its
Opacity to 75%.
3
Select the face
Choose the Fuzzy Select tool from the Toolbox.
In the Tool Options dialog, set the Threshold to
27. Make sure the Source layer is active in the
Layers dialog, and click in the upper-right area
of the image window. Use the Quick Mask to
clean up the selection around the neck and
lower-left of the face. Grow the selection
(Select > Grow) by 3 pixels, then cut it from the
layer (Ctrl+X). Finally, clear the selection by
clicking Select > None.
6
Gaussian blur
Duplicate the Brightness layer that you’ve just
created and name the new layer Gaussian Blur.
Open the Gaussian Blur filter (Filters > Blur >
Gaussian Blur). In the dialog, set both the
horizontal and the vertical Blur Radius values to
10.0 and the Blur Method to RLE (run-length
encoding). Click on OK to apply these settings
to the image. Next, in the Layers dialog, set the
Blur layer mode to Soft Light and the Opacity
level to 75%.
If you missed last issue Call 0870 837 4773 or +44 1858 438795.
www.tuxradar.com
LXF127.tut_gimp 81
January 2010 LXF127     81
20/11/09 3:37:43 pm
Tutorial Gimp
7
Merge face layers
8
In the Layers dialog, click the Eye icon to turn off the visibility of the
Background layer. Choose Image > Merge Visible Layers and in the
Layers Merge Options dialog, choose Expanded As Necessary. Click
Merge. The resulting layer will take the name of the lowest one. Turn
visibility of the Background layer back on.
9
Paint the backdrop
10
Starting around the edge of the face, paint wavy strokes on the
Watercolour layer. Do this until there’s a large amount of grey, but not a
solid block. Switch to the Smudge tool, tick Apply Jitter in the Tool
Options and smear the grey into random patterns. Feel free to skip this
step and the next, as they aren’t required for the dissolve effect.
11
Face pieces layer
Paint the foreground
Add a transparent layer, name it Watercolour 2 and move it above the
Source layer in the Layers dialog. Set the Foreground Colour to Black.
Use the Paintbrush tool’s Palette Knife preset to paint short random
strokes along the lower-right side of the face. Switch to the Smudge
tool’s Artistic Smudge preset to smear the strokes. Repeat as desired.
12
Click on the Source layer in the Layers dialog. Duplicate it, call the new
one Face Pieces and then move it to below Source. Make sure it’s the
active layer and choose the Scale tool. Click on the image window and
drag the left side of the Face Pieces layer to the left, almost to the edge
of the image window. Turn off the visibility of the Face Pieces layer.
Backdrop watercolour setup
Add a transparent layer (Layer > New). Name it Watercolour, and make
sure it’s above Background but below Source. Click the Smudge tool
and select the Artistic Smudge preset in the Tool Options dialog.
Choose the Paintbrush tool, set Fade Out length to 2500 and Scale to
2.0 in the Tool Options. Set the Foreground colour to a light grey.
Create a square brush
There are no suitable brushes for this project in the stock brush
collection or in GPS, so let’s create one. Open the Brushes dialog
(Windows > Dockable Dialogs > Brushes). Click the New Brush icon,
set the Shape to Square, the Radius to 50, the Hardness to 1 and the
spacing to 150. Name the brush Square 1; it’s automatically saved.
Never miss another issue Subscribe to the #1 source for Linux on p66.
82     LXF127 January 2010
LXF127.tut_gimp 82
www.linuxformat.com
20/11/09 3:37:45 pm
Gimp Tutorial
13
Mask the Source layer
14
Select the Source layer in the Layers dialog and add a white layer mask
(Layer > Mask > Add Layer Mask). Select the Square 1 brush. In the Tool
Options, set the Scale to 1, enable Brush Dynamics and tick to use a
random Size. Click, don’t stroke, over a wide area of the left side of the
face. Turn off the Watercolour layer’s visibility to see better.
15
Mask the Face Pieces layer
16
Choose the Paintbrush and select the Square 1 brush. In the Tool
Options, set Opacity to 100%, Scale to 0.80, enable Brush Dynamics
and tick Random Opacity and Size. Make brush strokes over a large area
of the left side of the image, including part of the face. Toggle the Source
and Watercolour layers’ visibility as needed.
17
Add drop shadow
Apply layer mask
The pieces floating away from the model’s face are not easily seen at
this point. To make them more visible, a drop shadow needs to be
added to the Face Pieces layer. Before doing this, the layer mask must
be applied to this layer. Click on the Face Pieces layer in the Layers
dialog and apply the layer mask (Layer > Mask > Apply Layer Mask).
18
Open the Drop Shadow filter (Filters > Light and Shadow > Drop
Shadow). Set the Offset X and Offset Y values to 4, the Blur Radius to 8,
the Opacity to 80 and untick the Allow Resizing option. Click OK to apply
the drop shadow.
Prepare to mask Face Pieces layer
Click the Face Pieces layer in the Layers dialog to activate it. Make the
layer visible again and add a black layer mask. Type D in the image
window to reset the Foreground and Background Colours to black and
white, respectively. Type X to swap the colours so that the Foreground
Colour is now white.
Add gradient mask to shadow
To make the pieces appear to be floating away from the face, add a
white layer mask to the Drop Shadow layer. Choose the Blend tool, set
Opacity to 100%, Gradient to FG to BG and Shape to Linear. Drag in the
layer mask from the right edge to the middle. If the pieces aren’t distinct
enough, duplicate the Drop Shadow layer once or twice. LXF
Next month It’ll be the last Gimp tutorial for a while, covering T-shirt designs.
www.tuxradar.com
LXF127.tut_gimp 83
January 2010 LXF127     83
20/11/09 3:37:46 pm

