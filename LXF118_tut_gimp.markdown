Tutorial Gimp Open source image-editing
Gimp
software you can get your teeth into
Gimp: iPod fun
Tune in to pop culture with Gimp. Michael J Hammel creates an iPod
advertisement faster than you can thumb your dial.
The iPod is the pop culture king these days. That title is due
in no small part to the simple yet fantastically fun advertising
campaign of silhouetted dancing yahoos with their high-
contrast iPods and bouncing earphone wires. What’s fun
about all this for regular readers of this column is the sheer
simplicity of the design. The iPod advertising artwork takes
only modest Gimp expertise, as long as you (and you know it’s
coming) start with good stock imagery.
In this month’s column I’m going to show you how to take
your own dancing fool and iPodicise him (or her) into
advertising nerdvana. No fancy tricks this month. All you need
for this tutorial is a little straightforward selection and layer
experience. So turn up the music and crank up Wilber. Let’s do
some Gimping.
Selecting a stock image
U
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
nlike many geeks, I’m not one to spend big bucks on
fancy gadgets. I tend to buy the cheap stuff from
online retailers and make it do the fancy stuff by
either shoving open source on the device or finding some way
to at least make it play nice with open source. My laptop is
one such beast. It wasn’t the top of the line Acer when I
bought it, but four years on both the laptop and its Gimpy
owner are still rockin’ with Tux.
Despite my cheap nature, I’m not averse to having
someone else gift me a fancy gadget. Fortunately for me, I
have a wonderful daughter who decided that this year I
needed a really nice holiday present. So she plunked down
the green and bought me a new iPod nano, an orange one to
match my Graphics Muse website, which is way cool (the
nano, that is). The daughter is way cool too. At least till we
return to the previously postponed gotta-have-a-car-for-
college issue. I may be walking to work next year. But at least
I have my tunes.
Finding photos of energetic music lovers on sites like
BigStockPhoto or iStockPhoto is no problem. The genre is
popular and photos abound. The dancers in the iPod adverts
all have one thing in common: their hands and feet are
typically recognisable even in silhouette. Keep this in mind
while searching online image archives. Another important
feature to look for in stock images for this project is solid-
coloured backgrounds, preferably white.
The two photos here are good candidates for this tutorial.
But take a look at the result of turning the woman into a
silhouette. The details of her folded arm and back leg are lost,
making the silhouette less recognisable than the man’s
Getting the images
The stock images used in this month’s column were
purchased from BigStockPhoto.com:
Dancing With Headphones (ID 4079419) female
The Dancer (ID 1805891) male
Folded arms are lost and a back foot just another fold in
clothing when placed in silhouette.
Last month We mixed Gimp up with Inkscape, Scribus and OpenOffice.org.
84 Linux Format May 2009
LXF118.tut_gimp 84
12/3/09 1:03:3 pm
Gimp Tutorial
Hands and feet visible in the silhouette make the dancing
male photo a better starting point for this project.
silhouette. In that image, the arms and legs stand out. There
will be some cleanup required to enhance the effect, but the
man is the better choice.
While the problem of hidden limbs would easily be
remedied in a silhouetted
video, with the subject’s
movement making the
outline more recognisable,
the problem isn’t easily fixed
in still life while keeping to
the simple silhouette. As I’ve
mentioned in previous Gimp tutorials, you should try
experiments like this on the comp images before you pay for
print-size images.
The chosen stock photo’s white background will make
creating a selection easy. There’s a light shadow beneath the
dancer but this won’t affect the complexity of the selection.
Keep in mind that the selection doesn’t need to be perfect.
Choose the Fuzzy Select tool from the Toolbox and click
on the white background to create an initial selection. For this
image the click should be near the light
shadow by the lower hand. Hold the Shift
key and make additional clicks to extend
the selection. Clean up the selection of the
background by growing the selection
(Select > Grow) by one pixel.
The selection created is of the
background, so invert it to create a
selection of the dancer. Copy (Ctrl+C) and
paste (Ctrl+V) the selection into a new
layer (Layer > New), and name the layer
‘Silhouette’ Enable the Keep
.
Transparency option for the
new layer, then fill the layer
with black. Remember that
it’s better not to modify the
original image so it can be
used again later if needed,
so add a new white layer
and move it below the
silhouette layer.
The dancer silhouette
needs a little cleanup. Notice where the scarf and jacket fall
away from the body in the original picture. In the silhouette
these are not helpful features. Use the Free Select tool to drag
selections around most of
these, then switch to Quick
Mask mode to detail the
area to be selected using a
hard-edged brush. Switch
back to selection mode and
cut the selections. Don’t fill
the selection with white! The silhouette is on a layer of its own
with transparency around it. Editing here should replace the
selected parts of the silhouette with transparency, so you
should cut the selections.
“The iPod advertising
artwork takes only
modest Gimp expertise.”
An accurate selection isn’t required for this project, but
the silhouette could do with a slight improvement.
Adding a
white layer
named ‘White
Background’
below the
silhouette
removes the
shadow from the
original image.
The iPod player
Creating the silhouette was simple, and creating the iPod is
just as easy. Since there isn’t a lot of detail in the device it can
be created in a separate image window, copied to the dancer
window and then scaled and rotated to fit. Scaling and
rotating will blur the detail of the device, but because it’s so
small and lacks detail this won’t be a problem for this project.
Normally a
soft-edged brush
is used to blend
edges into the
background, but
the iPod style
uses hard edges
with no blending.
If you missed last issue Call 0870 837 4773 or +44 1858 438795.
May 2009 Linux Format 85
LXF118.tut_gimp 85
12/3/09 1:03:4 pm
Tutorial Gimp
If the selection is no longer in Edit mode but the selection is still active then
just click inside the selection to go back into Edit mode.
Move the silhouette image out of the way for the moment,
but don’t close it. Open a new image window (File > New)
with a width of 380 and height of 420. The default is to open
the window with a background the same colour as the
background colour in the Toolbox. This isn’t important to this
part of the project, so if the background is some other colour,
don’t sweat it. We’ll drop the background layer a little later
anyway. For now, turn off the visibility of the background layer
in the Layers dialog.
Add a transparent layer to the image window, then choose
the Rectangle Select tool from the Toolbox. In the Tool
Options dialog, enable the Rounded Corners option. This will
display an option to set the radius, which you should set to
20. Drag through the image window to create a selection with
rounded corners. The exact dimensions are not important,
though the width should be smaller than the height. Reset the
foreground and background colours by typing X in the image
The iPod was created on a single layer so squeezing it
to make the dial circular is a simple operation that can be
done just by eyeballing it.
window, then drag the background colour (white) from the
Toolbox into the selection.
The selection will still be in edit mode at this point, which
means that the selection handles can be used to resize the
selection. Drag the four sides of the selection inward to form a
smaller rectangle centred in the upper half of the original,
white-filled rectangle.
Click on the Foreground Colour box in the Toolbox and
change the colour to a medium grey, with red, green and blue
set to 160. Close the dialog and drag the foreground colour
from the Toolbox into the selection in the image window. That
creates the iPod display window. Remember that this style is
very simple, so no additional detail is required, such as adding
depth around the display. Even if depth were added it
wouldn’t be seen after the iPod is scaled and rotated in the
dancer’s image.
Use the Ellipse Select tool to drag a circular selection
below the display window. The selection should span the
width of the display window, even if it’s not circular. Drag the
selection to position it in the centre of the lower half of the
iPod case. Once again, fill the selection with the foreground
colour. Clear the selection (Select > None). Use the Scale Tool
from the Toolbox to squeeze the iPod until the dial is the
familiar circular clickwheel.
Put the iPod in the dancer’s pocket
It’s a simple job to
resize the iPod for
the dancer.
Bring the silhouette image back into view with the iPod image.
Drag the iPod layer from the Layers dialog into the silhouette
image. Use the Scale tool to shrink the image to fit, then
rotate it to align with an imaginary trouser pocket. Hold down
Never miss another issue Subscribe to the #1 source for Linux on p102.
86 Linux Format May 2009
LXF118.tut_gimp 86
12/3/09 1:03:4 pm
Gimp Tutorial
the Ctrl key while scaling to keep the aspect ratio for the
device. Use the Rotate tool to rotate the iPod, then use the
Move tool to position near the pocket.
Add a white layer mask to the iPod layer. Use the
Paintbrush and a hard-edged brush to black out a small part
of the bottom of the iPod, leaving just part of the dial visible.
This simulates the iPod being in a pocket (though not for long
the way this guy is dancing).
The wires for the earphones come next in this project. Add
a transparent layer and name it Earphones. Before drawing
the paths, select a brush to draw the wires. The Circle (03)
brush works well with an image of this size. The selected brush
will be used to stroke the paths. Also, set the foreground
colour to white in the Toolbox by typing D followed by X in
the image window.
Perspective tool tips
The Perspective tool will open a dialog
when you click on the image window,
but this dialog is of little value to most
users. It shows a transformation matrix
which is nifty if you’re into math but of
little help to this type of design work.
Ignore the dialog and just drag the
handles in the image window. Then hit
the Enter key to accept the changes.
Also, the drag handles are not bound
to the viewable dimensions of the
image. Zoom out on the image window
to drag handles outside the visible edge
of the canvas. This will allow the
perspective layer to flow out to the
edge of the image and beyond. Of
course, what flows outside the visible
edge of the image won’t be included
in the final image, but that’s the
designer’s prerogative.
The shadow in this project didn’t flow
to the image borders but there is no
reason it couldn’t. In fact, adjusting the
shadow provides a very specific feel to
the design because it lets the viewer
know where the light is coming from.
Earphones: stroking paths
Choose the Paths tool from the Toolbox and click near the
dancer’s left ear (or where that ear should be). Without
releasing the mouse button, drag downward in the image
window. This extends the handles used to adjust the path.
Release the mouse button, then click and drag again where
the wire should meet the iPod. Use the handles to adjust the
shape of the wire.
Click on the stroke button at the bottom of the Paths
dialog. This will open the Stroke Path dialog. Choose to stroke
using the Paintbrush, which will use the brush selected earlier.
For added effect, click on the Enable Brush Dynamics option.
This causes the brush stroke to fade in and out at both ends of
the path. Finally, click on the Stroke button to apply the brush
stroke along the path. Repeat this process for a wire coming
from the right ear and connecting to the first wire at the chest.
The wires will probably require more fine tuning than
anything else in this project, since they and the iPod are
the most identifiable features.
The last major component of this design is a shadow
under the dancer. Like the silhouette, shadows in iPod ads
have hard edges. As it turns out, that makes it easy to create
the shadow.
In the Layers dialog, duplicate the silhouette layer and
rename the duplicate layer ‘Shadow’ Move this layer below
.
the Silhouette layer in the Layers dialog. Select the
Perspective tool from the Toolbox and click in the image
window to display the drag handles. Drag the upper-left
handle straight down and the upper-right handle down and to
the left, then hit the Enter key to accept the changes.
Add a white layer mask to the shadow layer, then type D in
the image window to reset the foreground colour to black.
Choose the Gradient tool from the Toolbox and in the Tool
Options dialog make sure the Gradient Reverse button is set
so that the gradient flows from white to black. Drag in the
image window from the dancer’s hand to near the upper-left
of the shadow layer to apply a fade out to the shadow. Finally,
reduce the opacity of the shadow layer to 80%.
That’s it. You can splash a little colour into this by adding
colour to the white background. In the end the simplicity of
the iPod style is what makes it both easy to identify with and,
for Gimp users, easy to reproduce. LXF
You may need
to move the
shadow layer
slightly after
applying the
perspective so
that it matches
up with the
dancer’s hand.
Next month We’ll turn up the heat for some hair flippin’ Gimp effects.
May 2009 Linux Format 87
LXF118.tut_gimp 87
12/3/09 1:03:5 pm

