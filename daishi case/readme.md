# Building a Case

This should just be a (relatively) quick guide on how to create a case for a Daishi, which ended up being super complex.

Step 1 is 3D printing the pieces. If you have access to a large enough 3D printer, you can just print the top and bottom as complete pieces using the .stl's in this folder.

If you are a mere mortal like me, you'll have to split up both the top and bottom case into a few pieces each. I included some .stl's that have been pre-split into pieces small enough to fit near any 3D printer, with dovetails to make alignment easier.

I print at ~50% infill (I try to push it as high as possible, but at around the 75% mark I start to get severe issues with print quality), with a brim, and 0.2mm layer height (could bump it up to 0.3 without a real loss in quality). A problem with printing in multiple dovetailed pieces is that fitment has to be pretty precise, and brims can fuck that up if not removed carefully. You can get away with whatever blade you have on hand, but I recommend using a metal deburring tool like https://smile.amazon.com/Acrux7-Deburring-Remover-Plastic-Aluminum/dp/B077Z4T437/ if you're going to be doing this a lot - it's been a big improvement to my 3D printing QoL.

After you have the pieces, you'll want to ensure they all fit together nicely and glue them together (I recommend a medium or thicker CA glue). This is also where I'd recommend painting, if you want to do so.

Use a soldering iron to put in your brass threaded inserts (links in the BoM). You could try to secure 3D printed components with something like wood screws, but I wouldn't recommend it. Brass threaded inserts are going to be way more durable than any threads you tap in plastic, which will allow you to actually take it apart and put it back together a few times. Plus you can actually get some clamp with these threaded inserts, which is pretty important for a build with gasketing.

This is "optional", but it makes a huge difference. Take some 1.75mm transparent filament and shove it in the holes for the lock lights, using a flush cutter to get the top flush with the top of the top case (make sure the filament ends a few mm above the bottom of the hole, so that there's room for the LED). This makes for a really nice looking light pipe, and when the lights are off it almost just looks like the case material; I love the aesthetic.

Now it's time to apply the gasketing. Take your rubber of choice (I use neoprene, but It also works with EPDM and probably silicone and most any other rubber too) and start punching out holes. I got this cheap set off amazon https://smile.amazon.com/gp/product/B07BT47968 but the only sizes you need are 5mm, 2mm, and 7mm (and really 95% of the work is done with the 5mm punch, with the others only used for the standoffs with screw holes). Cut out a bunch of strips of rubber to go around the edge of the bottom case and the bottom of the top case (as seen in the photos), and glue everything in!

I use some blu-tack to hold down my cable that goes to the USB daughterboard (velcro would be nicer but I only had hooks on hand and no loops!)

You'll need 8 M3x12 screws for joining the top and bottom case, and 11 M2x4 screws to mount the keyboard PCB and daughterboard (though you could also forgo the 7 screws for the keyboard PCB and just rely on the gasketing). I also recommend using M2 fiber washers for the PCB screws (linked in the BoM).

That's pretty much it for building the case. Good luck!
