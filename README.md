# skate-bis-tools

Software tools to use with the openSource(skateboards) Board Identification System (TM)

See http://www.opensourceboards.com/skateboards/the-board-identification-system/

All skaters are familiar with deck width and length which are pretty solidly defined as you'd imagine. Further parameters such as nose and tail length, wheelbase, etc. are slightly wooly with respect to where measurements start and end - e.g. nose length could be based the old-school 2.5" truck bolt hole pattern and wheelbase is sometimes measured axle to axle which is meaningless without a known truck geometry. The BIS as it stands is a good starting point for standardisation of measurements but currently rather limited for "exotic" deck designs. Of course, engineering drawings can be produced that are completely unambiguous. That said, we want to expand on BIS to encompass the geometry of our favourite deck shapes, especially in the field of freestyle deck designs which can be very exacting in their requirements!

The initial plan is to provide an Inkscape extension that will make a simple deck drawing from various BIS parameters. This will allow a simple text description of a deck (e.g. from a database) to be automatically oulined as a drawing (in SVG or similar standard format) for use on websites and other communication media.
 
Initially just have inputs for simple symmetrical decks: -

* W – width, in inches
* L – length, in inches
* A – angle of nose and tail (symmetrical), in degrees
* R – radius of concavity, in inches (see resources page to understand how much drop there is from the center of the board to the edges)
* N – nose and tail length (symmetrical)
* D – horizontal length of kicktail (symmetrical)
* T – transition distance between flat kicks and full concave, in inches
* E – edge style, in edge style number (see specific drawings for detailed dimensions)

So we will need to enhance the model: -

* the non-symmetrical attributes will need to be added (already in BIS but not for interesting shape profiles)
* less emphasis on imperial units perhaps!
* nose and tail shape designers - currently just a design number - 
* edge shape designers - currently no parameters for it 
* get community input on extensions to the scheme to include rocker, etc. People to involve: Bob Loftin, Tony Gale, Simon Mrozinski
* more elaborate concave shape specifiers - especially non-radiussed - more of mold shape than anything else

Then to the laser cutter or CNC machine for mold making!

A deck is only part of the story: truck and wheel geometry is very important and some standard parameters should be defined.

