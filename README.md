# isortho
My first attempt at creating a keyboard - an ISO orthonlinear 65-ish keyb

## Background

I became fascinated by keyboards around 2017, bought some really unorthodox ones, continued with 65%, keycaps, etc. etc. r/mechanicalkeyboards is a constant source of ideas.

Exploring the concept of how a keyboard should actually look in terms of layout I had my eyes on the ortholinear stuff like the Plank, stumbled across the Atreus, which I of course got one.
The Atreus is a 40% keyboard which has the keys in vertical columns but staggered horizontally to match the length of your fingers.
I also got very interested in the [Fletcher keyboards](https://thejoeblankenship.com/blogs/fletcher_keyboard/fletcher_keyboard.html), which has a similar concept.

But it is prohibitivly hard to learn to type effortlessly on a 40% keyboard, but I liked the ortholinear concept.
It's just stupid that the non-balanced staggering of the keys on a normal keyboard.
The limitations of a mechanincal construction in the beginning of the previous should not limit us.
As humans we can adopt to many things, but we should not need to.

So, I looked around for a 65% ortholinear keyboard, but only found a few, the defunct Terminus 2 really looked promising.
I'm also Swedish so I wanted a ISO-feel.
In short I had to try to make my own 65% orthonlinear ISO keyboard, the idea of the `isortho` was born.

But I did not stop there, I wanted a keyboard with a layout that is as close to the "normal" as possible, but also have the possibility to get nice keycaps easy(ier).
So the `isortho` is a keyboard where the rows from a normal ISO keyboard has been straightened so that they are vertical.
The goals is also that most of the non-alphanumeric keys are the same size as on a normal keyboard, or at least common in custom keycap sets.

## The method

- Make some statistical analysis of which size of keycaps are most often available in custom keycaps, e.g. if almost all kits have a 3U space bar, the layout should have that rather than a more uncommon 4U spacebar
- Design a layout in [Keyboard Layout Editor](http://www.keyboard-layout-editor.com/)
- Import the JSON definiton of that into [Keyboard Firmware Builder](http://www.keyboard-layout-editor.com/) where you also get your wiring diagram, QMK compatible firmware and a lot of other cool stuff!
- Create the layout in KiCad using the help of guides like the one from [ruiqimao](https://github.com/ruiqimao/keyboard-pcb-guide)
- Produce a PCB (maybe from [JLCPCB](https://jlcpcb.com/))
- Produce a plate and case ([Plate & Case Builder](http://builder.swillkb.com/) )
- Get switches, stabs, keycaps and all the other stuff
- Put it together and cross your fingers!

## Current state

I have a tentative layout, need to research best set of key sizes to optimise fit for key sets.

I've done some tinkering with KiCad so I think I understand that process.

So, it's just the rest!
