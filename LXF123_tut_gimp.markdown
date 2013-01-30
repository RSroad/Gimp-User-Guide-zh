Tutorial Gimp Open source image-editing
Gimp
software you can get your teeth into
Gimp: Travel to
Revel in the majesty of creation as Michael J Hammel fires up the Gimp
and leads you through the process of making some stunning stellar art.
This is looks like The Big Bang Theory’s opening credits,
but it’s really the result of this month’s project.
L
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
ast month I promised to show you how everyday
objects could be used with a scanner to create fun
projects. Unfortunately, while I was working towards
that goal, my scanner died, but Marco had more luck, as you’ll
see on page 86. With my trusty scanner heading for the tip, it
was time to fall back on those creative skills we’ve been
developing recently. And what better way to get creative than
to spawn our own star field? Even better, this process
requires no stock images and very few Gimp tools. For
something so stunning, it’s pretty straightforward. The
method I’ll walk you through here is based on Gimp 2.6, but
the same process can be applied to Gimp 2.4 with a few
menu changes.
A simple process
Creating a star field that goes beyond realism and enters the
realm of fantasy is fairly simple. All you need to do is:
Create a background star field.
Create a collection of larger stars.
Cluster the stars.
Add larger, brighter foreground stars.
Colour the star field.
Add some coloured dust.
Throw in a planet or ship.
The last step is the hardest, although Gimp’s Sphere
Designer makes creating planets pretty easy. Other than that,
you’ll probably spend most of your time in this project getting
the star clusters just right.
The core of this process is using noise filters to produce
random dots on a black background. However, these dots are
too small for a typical project, especially one bound for print.
To get around this, we start with a small scale version of the
stars and scale the image up. I wouldn’t normally recommend
scaling up raster images like this, but it’s an ideal way to
produce the effect we need for this project.
Getting started
The first layer will contain the distant, background set of
stars. Start by creating a new image that’s 640x480 pixels in
size with a white background. Type D in the image window to
reset the foreground and background colours to their default
settings of black and white respectively. Drag the foreground
colour from the toolbox into the image window to fill the
background layer with black.
Add a new layer (Layer > New Layer) and name it Small
Stars. Set the layer colour to the foreground colour, open the
HSV Noise filter (Filters > Noise > HSV Noise) and set the
Holdness to 3, the Hue to 20, the Saturation to 90 and the
Value to 100. Apply this to the Small Stars layer by clicking
the OK button. HSV Noise renders coloured noise, so we need
to desaturate it. Go to Colours > Desaturate and use the
Luminosity setting. Click OK to apply this to the layer.
The very small points of light we’ve just created are really
hard to see on a monitor, so zoom into the image window by
300%. We’ll zoom back out when the contrast in the image
will be easier to see in print.
The rendered noise is randomly distributed, but it’s a bit
too densely populated. Open the Brightness/Contrast dialog
(Colours > Brightness/Contrast). Set the Brightness to 45
Last month We created a warp speed effect that Kirk would be proud of.
82 LXF123 October 2009
LXF123.tut_gimp 82
www.linuxformat.com
30/7/09 3:27:39 pm
Gimp Tutorial
the stars
Planet settings
The original
(far-left) is filled
with stars while
the updated
version (left) has
fewer stars.
Remember: this
is a zoomed-in
view. The left
image might look
all right, but it’s
far too cluttered
at actual size.
and the Contrast to 65. The result will be fewer stars, although
the remaining stars will be a bit brighter.
These settings are variable, meaning that changing them
can have an important effect on the final appearance of the
image. Increase both values to reduce the number of small
stars even further, but be careful not to make the stars too
bright. Remember that these are background stars – the
more visible clusters are yet to come.
Grow bigger stars
Next up are some larger, closer stars. Duplicate the Small
Stars layer (Layer > Duplicate) and then name the new layer
Large Stars. Thin out the stars a bit more with the
Brightness/Contrast dialog, setting the Brightness to 50 and
the Contrast to 110 this time. Now scale the layer up to 200%
(Layer > Scale). Using a percentage value will make it easier
to scale this layer back down again later.
Scaling the layer up without scaling up the image will
make the layer larger than the image size, but don’t panic.
The next few steps will still work on the entire layer and
resizing later will fit the layer back into the image again.
Now open the Levels dialog (Colours > Levels). Set the
Black Point to 230, the Mid Point to 1 and the White Point
to 250. The Levels adjustment will sharpen the large stars,
making them darker and more distinct. You might find that
Inverting the colours makes it easier to choose the right
settings for the Levels adjustment. You could also experiment
with higher values for the Black and White Points.
Once you’re happy, the layer can be made smaller again,
but not all the way back to its original size. That would mean
scaling it to 50% (or half its current size), but we want to
Scale the layer down by 40% instead. The stars will be just
a bit larger. If this isn’t large enough, scale down by smaller
amounts. But don’t make these stars too large, because
the clustering process we’ll use later will bring out brighter,
larger groups of stars. After you’re done scaling, fit the layer
to the image, using the Layer > Layer To Image Size option,
essentially trimming the excess off the layer.
Working at a larger scale
Now it’s time to scale up the entire project. Scaling up will
produce a much better star field for print or the web. It also
makes the rest of these steps easier to see. I recommend you
Scale the image up (Image > Scale Image) by 250%. Using a
percentage value will keep the aspect ratio, so the stars
remain round. Set the Large Stars layer mode to Screen. Now
the entire set of small stars and larger stars should be visible.
The new image size should be 1600x1200 pixels in size.
At this point you’ll get a better feel for how well your Levels
adjustment worked in the previous step. If the large stars are
too bright, apply another Levels adjustment or change the
Brightness/Contrast to darken them a bit.
Space voids
So far we’ve created a nice enough field of stars, but there are
plenty of improvements that can be made. The first is to
create some voids in space. To do this, add white layer masks
(Layer > Mask > Add Layer Mask) to both the Large Stars and
Small Stars layers. Choose the Paintbrush from the toolbox
and select a fairly large brush. In Tool Options, set the initial
Opacity for the Paintbrush to 50%. Type D in the image
window to make sure the foreground colour is reset to black.
Credit where it’s due
Using the Luminosity setting when desaturating the stars
helped to make them brighter and more visible. Currently
the whole star field is too uniform, though.
This tutorial is based on the process for
making realistic star fields described by
Greg Martin on his website. I’ve
translated his ideas into a Gimp-specific
method, but the basic process is his. The
tutorial isn’t linked from his website,
though, and I found it listed in a
collection of Photoshop tutorial links.
However, the direct link still works:
http://gallery.artofgregmartin.com/
tuts_arts/making_a_star_field.html.
Also, check out Greg’s wonderful
galleries of inspiring designs at
http://gallery.artofgregmartin.com.
If you missed last issue Call 0870 837 4773 or +44 1858 438795.
www.tuxradar.com
LXF123.tut_gimp 83
October 2009 LXF123 83
30/7/09 3:27:40 pm
Tutorial Gimp
Part of the
process involves
dealing with an
oversized layer
that extends
beyond our
canvas. Don’t
worry, though,
the changes you
make will be
applied to the
invisible parts of
the layer as well.
Now paint liberally throughout the Small Stars layer, wiping
out large swathes of stars and leaving a few clusters behind.
Increase the size of the brush and repeat the process on the
Large Stars layer. Try out different brushes and adjust the
Opacity of the brushes as you go.
You should try to avoid any obvious patterns and remove
any regularity created when the Brightness/Contrast and
Levels adjustments were applied to the original HSV noise.
Use short brush strokes, alternating vertical and horizontal
stroke directions. This step seems awkward at first and there
are no rules for which parts of the fields to wipe out. It’s up to
you, but keep in mind that the goal is to create some blank
regions of space. Don’t be shy on the Large Stars layer either
– we won’t need many big stars left for the next step.
When the voids are plentiful and obvious, save the project
in XCF format so that if the remaining steps don’t work out,
you can try again without having to start from scratch. Finally,
flatten the image (Image > Flatten) into a single layer.
Clustering
The real artistic aspect of this project is in the clustering of
stars. To create clusters, use the Clone tool from the toolbox.
Again, a variety of brushes may be required here, but it all
depends on your tastes. Hard-edged brushes seem to
produce the best effects, but don’t be afraid to experiment.
You can change
the intensity of
your stars with
the Brightness/
Contrast dialog –
don’t make them
too bright.
This is more like it. The Star Glow layer is used to bring
out detail in the clusters of stars while leaving the
background pinpoints of light essentially untouched.
To use the Clone tool, hold down the Ctrl key and click
anywhere in the image window. This becomes the source
location. Release the Ctrl key and begin painting anywhere in
the image window to duplicate what’s in the source location.
Note that the source location moves relative to the brush,
always staying exactly the same distance and direction away
from the current location.
Cloning with the Normal mode in the Tool Options will
simply replace the current pixels under the cursor with the
pixels from the source location. To get really good clusters,
alternate between Normal, Screen and Overlay modes in the
Tool Options for the Clone Tool. Use areas with stars as the
source location when creating clusters.
This step takes practice to get just right. Try to create
some swirling clusters or a spiral galaxy as seen from above.
Attempt a few operations to see what you get, then use
Ctrl+Z to undo those changes and try again. Once you begin
to see how the clusters form, you won’t need to reverse your
changes. Save your work frequently and in different files as
you experiment. This will enable you to return to a particular
variation later if your experiments get out of hand.
The project is really taking shape at this point. The next
step is to add a soft glow from the star clusters. Duplicate the
background layer and name the new layer Star Glow. Open
the Gaussian Blur filter (Filters > Blur > Gaussian Blur) and
set both the Horizontal and Vertical Blur Radius to
somewhere between 5 and 40, depending on the density of
your clusters. Choose a cluster with the most visibly distinct
Reduce the Opacity of various layers, including the Star
Glow layer, to bring out some of the subtle colouring.
Never miss another issue Subscribe to the #1 source for Linux on p102.
84 LXF123 October 2009
LXF123.tut_gimp 84
www.linuxformat.com
30/7/09 3:27:42 pm
Gimp Tutorial
Experimentation is key to this project. Try out different
Gradient Flare presets and find the effects you like.
white dots in the Preview window of the Gaussian Blur dialog
and adjust the Blur Radius based on that preview. The result
should be a cloud-like appearance around the stars. Set the
Star Glow layer mode to Dodge if you want a subtle
enhancement or Screen for a more vivid change.
Now it’s time to improve the glow with a tinge of colour.
Open the Colourise dialog (Layers > Colourise) and set the
Hue, Saturation and Levels to 215, 90 and 0 respectively.
Colouring
Duplicate the background layer and name the duplicate layer
Red Stars. Move this layer to the top of the layer stack.
Reduce the number of visible stars using the Levels dialog
and then set the Black Point to 90, the Mid Point to 1 and the
White Point to 160, although these values can be adjusted as
necessary. Open the Colourise dialog (Layers > Colourise)
and set the Hue, Saturation and Lightness sliders to 0, 80 and
-10 respectively. Now set the Layer Mode for the Red Stars
layer to Dodge.
Repeat this process as many times as you like, using
variations on the Levels and Colourise settings to add various
different tints to the star field. You can also use a Layer Mask
to selectively colour sets of stars in these colouring layers.
Lens and gradient flares
The bright points of light in the star field need to be softened
and broadened, so we’ll employ the Lens Flare and Gradient
Flares filters. First, create a new layer (Layer > New) that’s
250x250 pixels in size. Set the Fill Type to Foreground Colour
(this should be black) and name the new layer Lens Flare.
Move this layer to the top of the layer stack.
Open the Lens Flare filter (Filters > Light and Shadow >
Lens Flare) and click on OK to render the flare in the Lens
Flare layer. The flare is coloured, so desaturate it with Colours
> Desaturate, although you could also experiment with
coloured flares. Set the Layer Mode to Dodge and use the
Move tool to drag the flare over a cluster of stars.
Duplicate the flare a few times, scaling each copy up or
down a bit, and position the duplicates near various star
clusters. Placing the centre of a flare over space voids will use
just the outer edges of the flare to highlight an area. Placing a
flare directly over a star will make it shine even brighter.
Now create another black layer that’s 250x250 pixels in
size. Set the Layer Mode to Dodge and name the new layer
Gradient Flare. Open the Gradient Flare filter (Filters > Light
and Shadow > Gradient Flares). In the Selector tab, choose
the Hidden Planet, Bright Star or Distant Sun preset. Render
this into the new layer. Desaturate and position it as you did
with the lens flares, repeating the process several times.
Space dust
Add a transparent layer (Layer > New), name it Space Dust
and move it to the top of the layer stack. Set the Layer Mode
to Screen and the Opacity to 20%.
Pick a new foreground colour – try a soft blue with the
RGB values set to 57, 99 and 176 – and choose the Paintbrush
from the toolbox. Choose a variety of soft brushes and
change these often as you paint. If you’re using the Gimp
Paint Studio package, start with the 6_Pincelada100 brush.
Otherwise, choose any soft-edged brush. In the Tool Options
dialog, set the Opacity to 20%. Now paint space dust in long
strokes horizontally, vertically and diagonally. Fill the layer
with more dust than you need, then use the Eraser to remove
the excess.
Adding a planet
The star field is complete, but you could add a foreground
planet to spice it up a little. The Sphere Designer filter makes
creating planets simple. Create a transparent 600x600 layer
named Planet. Open the filter (Filters > Render > Sphere
Designer). Notice that there are three default layers. Each can
be edited and you can add more, although new layers are
added at the bottom of the stack and you can’t change their
order. The complete list of settings used to create a planet
can be found in the magazine section of your LXFDVD. LXF
The planet’s
size and colours
were adjusted
after rendering
to make it blend
in well with the
rest of the image.
Space dust serves essentially the same purpose as the
Star Glow layer – softening up the bright clusters. However,
it also adds some colour to the space voids.
Next month We’ll use Gimp Paint Studio to create a retro sunburst design.
www.tuxradar.com
LXF123.tut_gimp 85
October 2009 LXF123 85
30/7/09 3:27:43 pm

