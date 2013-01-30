Tutorial Gimp Open source image-editing
Gimp
software you can get your teeth into
Gimp: Going to
Want to explore strange new worlds and seek out new inspirations in your art?
Michael J Hammel shows you how to make the jump using Gimp.
displays. Most importantly of all, this is a do-it-yourself
project, so there are no stock images to track down this time.
I’ll also be going into a little more detail than I have in previous
months in order to help you if you’re new to these articles and
still leaning toward the beginner level.
Prepare to engage
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
fter two months of you being patient while I indulged
my creative side, it’s time for a tutorial that is a bit
more repeatable and not quite so complex. If you’ve
spent your time this summer anywhere except hiding behind
Saturn’s moon, you’ll know that a stellar rebirth brought a
rejuvenated Star Trek back to the cinema. In homage to this
re-envisioning, this month I’ll show you how to add a warp
speed effect to your projects.
What we’re looking for in this project is an outcome similar
to the warp speed effect in the original Star Trek: The Motion
Picture movie from so many years ago. For those of you who
haven’t dusted off your trekkie memory banks in a while, let’s
recap: the USS Enterprise engages warp speed and pulls an
asteroid in with it, turning the warp field into a wormhole.
Everyone goes motion-blurry for a few minutes until they
destroy the rock. Then Kirk goes all superior on his number
two for making him look bad. Here, we’re going to follow our
shipmates into warp space and leave the wormhole stuff for
the navigator to figure out.
Open a new image window with a white background set to
1250x1250 pixels. Note that this tutorial will work better with
a square image window, because of the rotations we’ll be
performing near the end of the process. Now the size of the
image might be a bit large for your project, or it could be a bit
too taxing for your computer to handle. If that’s the case, just
halve all the pixel counts. The end results should be
essentially the same at half the size.
Choose Rectangle Select from the toolbox and draw a
rectangular selection anywhere in the image window. The size
and position of this initial selection don’t matter, because
we’re about to change it manually. In the Tool Options dialog,
set the Size to 1250x40 pixels and the Position to 0x605. This
will create a selection 40 pixels tall that spans the width of the
image window and is centred on our canvas.
Complete the selection by hitting Enter. Copy (Ctrl+C) and
paste (Ctrl+V) the selection to a new layer. Name this new
layer Noise. Open the Hurl filter (Filters > Noise > Hurl) and
set the Random Seed to 10, the Randomisation to 1% and
For the cadets
Although there are a lot of steps to follow for this tutorial,
none are particularly complex or require anything other than
the stock features found in the latest version of Gimp (2.6).
We’ll only be creating a few layers too, which means this
project won’t be too taxing on slower systems or small
If a Scotsman complains that the Gimp “cannae take any
more Cap’n,” don’t believe him.
Last month We turned up the heat and created a beautiful fire goddess.
82 LXF122 September 2009
LXF122.tut_gimp 82
www.linuxformat.com
3/7/09 1:18:4 pm
Gimp Tutorial
warp speed
immediate update to the other field. However, as only the
Height needs to be scaled here, you should click on the link
icon to the right of these two fields so that the link appears to
be broken. This will let you change the Height and Width of
the object you’re scaling independently of each other.
Since the layer we’re working with was initially centralised,
the scaling should keep the Noise layer directly aligned with
the background. If it doesn’t, use the Align tool. This tool
requires you to click on each layer, one at a time, in the image
window to align them. So, aligning the Noise layer with the
background means clicking on the Background layer first,
followed by the Noise layer and then using the Relative To
option. Since this process shouldn’t be necessary, I’ll leave it
as an exercise for the curious reader.
With the Noise layer active in the Layers dialog, merge
(Layers > Merge Down) the Noise layer with the background
layer. Doing this will give the merged layer the same name as
the bottom of the
two layers that
were merged, so
Background in this
particular case.
Now it’s time to
invert the colours
(Colours > Invert). Suddenly, the project begins to take shape,
but the streaks need to flow from the outer edges of the
image window towards the centre. The first step is to map the
image into polar coordinates.
Open the Polar Coordinates filter (Filters > Distorts > Polar
Coordinates). Set the Circle Depth to 0 and the Offset Angle
to 0. If the former isn’t set to 0, the distortion won’t map to
the full size of the square image window. Technically, the latter
could be set to anything, but I’ve chosen to use 0 to make it
easier to remember this process. There are three options at
Quick
tip
The number of
streaks all depends
on the amount of
noise in your Noise
layer. Increase the
noise if you want
more streaks.
“Rescaling will stretch
the dots from the noise
into vertical streaks.”
It looks like we’re not making use of all our canvas space,
but don’t worry – soon this will be a streaking warp field.
Repeat to 2. Click OK to apply the settings to the Noise layer.
Note that the Random Seed and Repeat values can be
changed as you desire and increasing the noise will produce
more warp streaks. However, too much noise will clutter the
final product with streaks, so don’t overdo it.
You’ll probably notice that the Hurl filter has essentially
thrown dots of colour on the current layer within the
selection. This project doesn’t need the colour, though, just
the dots. Desaturate (Colours > Desaturate) the Noise layer
using the Luminosity setting. Luminosity brings out the dots
better than the Lightness and Average settings, but feel free
to choose a different Desaturation option if you prefer.
The contrast between the space and the dots can be
improved further using the Levels dialog. Set both the Black
Point and White Point, represented by eyedroppers between
the Input Levels and Output Levels graphs, to 180. Click OK to
apply this change.
When dots go streaking
At the moment the colours are inverted for the warp speed
effect (the dots are black and the background is white), but
this will be addressed momentarily. Before that, the Noise
layer needs to be rescaled to fit the image window. Rescaling
will stretch the dots from the noise into vertical streaks.
Scale the Noise layer (Layer > Scale Layer) to 1250x1250
pixels. The Scale dialog keeps the aspect ratio by default,
which means changes to either Height or Width cause an
This close up shows the Levels adjustment has darkened
the noise (before is upper left and after on the lower right),
which will improve the visibility of our warp streaks later.
If you missed last issue Call 0870 837 4773 or +44 1858 438795.
www.tuxradar.com
LXF122.tut_gimp 83
September 2009 LXF122     83
3/7/09 1:18:5 pm
Tutorial Gimp
The Scale dialog defaults to changing Height and Width Curves provide a useful way of enhancing the contrast of
proportionally, but clicking the link icon will alter that. our warp streaks for a more potent effect.
the bottom of this dialog: Map Backwards, Map From Top and with Filters > Blur > Motion Blur. Be aware that the preview
To Polar. Only the To Polar option needs to be set. The other window may be slow to update depending on your system’s
two aren’t necessary for this example, but setting them resources, so you may need to be patient. Set the Blur Type
  shouldn’t adversely affect the final results. to Zoom and centre the effect at X = 625 and Y = 625, making
    The streaks in the image might be too bright or too dim at sure that the Blur Outward option isn’t set. The Length
    this point, depending on the work you did with the Noise layer parameter should be somewhere around 50 to 100 – note
    earlier. If they’re too dim, duplicate the Background layer and that larger values will stretch the streaks more, but might dim
      set the duplicate layer’s Layer Mode to Screen. If there are them too much. In this example, the length was set to 100.
        too many streaks, set the Layer Mode to Overlay instead. There are several steps that can be performed at this
        Once that’s done, you should merge the two layers. point to improve the streaks. If the streaks are too dim,
                                                            duplicate the layer and set its Layer Mode to Screen, then
                                                           merge the two layers. If this causes too many new streaks to
                                                          appear, these can be addressed by using the Curves or Levels
                                                         dialogs. Here, I used the Curves dialog to adjust the Value
                                                        curve (as shown in the screenshot above), brightening nearby
                                                       streaks and removing dimmer streaks from view.
Stretching the field
Quick
tip
There’s not much
colour in this image
compared with the
black background.
This makes using
most layer modes
impractical, since
many will subtract
the streaks right
out of the picture.
The image should now look like a bad approximation of the
warp speed effect. Fortunately, Gimp gives us the tools to
make it better. Applying the Polar Coordinates filter stretches
the streaks slightly, but they need to be lengthened even
further. This is done using the Motion Blur filter, so open it up
Applying the Polar Coordinates filter to the inverted
streaks creates the foundation of the warp speed effect.
Colouring the field
Before we get on to the final few steps, it’s time to add colour
to the plain white streaks to make them more reminiscent of
Star Trek: The Motion Picture’s effect. Before starting, ensure
you have just one layer, which should be the Background
layer. If there are more layers than that, merge them until only
the background remains. Duplicate the Background layer.
Open the Colourize dialog (Colours > Colourize) and set the
Hue to 220, Saturation to 90 and Lightness to -40, then apply
these settings to the layer. Name the layer Blue, because
these values will colour the streaks blue. Now set the Layer
Mode to Screen and rotate the layer 90 degrees clockwise
(Layer > Transform > Rotate 90 Clockwise).
With the blue tint added, it’s time to add some red streaks
to our effect. To do this, select the Background layer in the
Layers dialog again. Open the Colourize dialog as you did
before, but this time set the Hue to 360, the Saturation to 60
and the Value to -40. This will tint the layer red. It’s worth
noting that setting the Blue layer’s Mode to Screen is what
allows the red streaks to show. In an image such as this –
made up of black and one other colour – the Screen mode
acts similarly to the Addition mode, where the pixels in the
Never miss another issue Subscribe to the #1 source for Linux on p102.
84     LXF122 September 2009
LXF122.tut_gimp 84
www.linuxformat.com
3/7/09 1:18:6 pm
Gimp Tutorial
Rotating the upper layer offsets the streaks, and setting
the layer to Screen allows the red coloured streaks on the
lower layer to show through.
Screen mode layer are added to the pixels in the layer below.
Black pixels in the Screen mode layer won’t change the
appearance of the pixels in the layer below, however.
A few adjustments
We’re close to our final product, but the intensity of the
streaks can be improved. Select the Background layer and
open the Levels dialog. Set the Black Point field to 25 and the
White Point to 170. Now select the Blue layer and open the
Layers dialog again. This time set the White Point to 170,
leaving the Black Point at 0.
Creating a central star
The image is essentially done at this point, but there’s one
more thing we can do to spice things up a bit. It’s time to add
a central star at the focal
point of the warp field.
There are many ways
we could achieve this
effect. For example, we
could use the Paintbrush in
tandem with a soft-edged
brush, scaled appropriately. The Super Nova filter could be
used or, to get really fancy, we could employ the Sphere
Designer filter’s skills. However, the method I’ve chosen for
this project is the Gradient Flare filter.
Start with a new transparent layer. Name this layer
Gradient Flare. Now fire up the filter via Filters > Light and
Shadow > Gradient Flare and click on the Distant_Sun entry
in the Selector tab. At the bottom of the dialog, click on the
Copy button and name the copy Warp Speed. With the new
entry highlighted, click on the Edit button to open the
Gradient Flare editor.
In the General tab, set the Glow Paint mode to Normal and
the Opacity to 100, Rays Paint mode to Normal and Opacity
to 90, and the Second Flares to Normal with the Opacity set
to 0. This gradient flare won’t use the Second Flares. Now
select the Glow tab, set the Radial Gradient to %white_grd,
the Angular Gradient to %white and Angular Size Gradient to
%white. Under the parameters
set the Size to 10%, the Rotation
can be left at 0 and the Hue
Rotation left at 55.0.
In the Rays tab set Radial
Gradient to %white_grd, Angular
Gradient to %Flare Glow Angular
1 and the Angular Size Gradient to %random. Under the
Parameters you need to set the Size Percent to 104, Rotation
to 140, Hue Rotation to -12, Number Of Spikes to 63 and
Spike Thickness to 90.
Finally, click OK to accept the changes to the Warp Speed
flare, and then click OK again in the Gradient Flare dialog to
apply the flare to the transparent layer we created earlier. The
flare can be coloured using the Colourize dialog. Here, I tinted
the flare with yellow.
“Black pixels in Screen
mode won’t alter the
look of the layer below.”
Editing the
Gradient Flare
dialog will
produce the
distant star in
the warp.
Quick
tip
A distant star field
behind the warp
field is another
optional step.
Create a noise layer,
desaturate it and
place it on the top
of the layer stack.
To hide the stars
behind the streaks,
add a layer mask
and copy all the
streak layers to it.
Finishing touches
After some adjustments you should see brighter streaks
near the edges, tending toward blue, that fade away.
The last step in our process is optional – so try it out and see
if you think it improves your work. When I reached the end of
this tutorial, I found that there was quite a bit of pixellation in
the streaks when I viewed the image at full size (I typically
work on these projects while zoomed out a bit). To
compensate, I applied a Gaussian Blur of three pixels to each
layer. This lightens the image slightly, so further adjustments
using the Levels or Curves dialog may be required. LXF
Next month Scan everyday objects as an alternative to stock image sites.
www.tuxradar.com
LXF122.tut_gimp 85
September 2009 LXF122     85
3/7/09 1:18:7 pm

