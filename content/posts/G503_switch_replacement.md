+++ 
draft = true
date = 2025-07-19T11:50:04+01:00
title = "Logitech G503 Switch Replacement"
description = "Replacing the two main switches in my G503 which were now causing click issues."
slug = "G503 Switch Replacement"
tags = ["logitech","electronics","repair"]
categories = ["repair"]
externalLink = ""
series = []
+++


I am not one to frivolously spend money, so when my Logitech G503 mouse buttons started behaving erratically, I was hesitant to buy a new mouse. I saw this guide[^1] on Reddit and thought this looks pretty straightforward, mine isn't a G502 but a G503 is just a G502 with battery...right? How hard can it be? Well, not that difficult but definitely required a lot more work than the guide shows.

# The Switches
I settled on the D2F-01F (although after reading another thread, perhaps I should have gone for some Huano[^2]), I ordered a pack of 5 for ~£5 from [DigiKey](https://www.digikey.co.uk/en/products/detail/omron-electronics-inc-emc-div/D2F-01F/83266).

# Disassembly
## 1. Seperating the Top and Bottom of the Mouse Shell
The first step is to remove each of the slide pads on the bottom side of the mouse. Each of them have screw underneath except for the one that surrounds the sensor.

After removing the pads unscrew these 4 screws.

![Skate pads off](/images/G503_Pad_off.jpg)

Then use a prying tool, I am this one from my iFixit kit. 

SHOW TOOL

It was at this point I knew it was going to be a more difficult task than the guide showing the G502. At this stage in the G502 guide, the top of the shell came off revealing all of the boards below. 
However, in the G503 the boards are split. Some are screwed into the bottom of the mouse and the rest are screwed into the top shell at the bottom (or top depending on how you look at it), is the board that I wanted to get to.

Carefully remove the 2 ribbon cables and the battery connector. You can then set the bottom part with PCB aside, we won't be needing this. 

![Connectors](/images/connectors.jpg)

## 2. Removing the Button Assembly
Within the top shell is an assembly consisting of a few PCB's, one of which houses the switches we are after. This assembly is held in with a tonne of screws, to even be able to access them all we must first remove the outer plastic panel with the Logitech G logo. That is done by removing these two screws and some carful use of the prying tool.

![G Panel Screws](/images/GPanelScrews.jpg)

Underneath the Logitech G panel will be another 3 screws. Remove the one holding in the white LED shroud.
![White Light Shroud]

Now to remove the Button assembly we have to remove the following X amount of screws.
- 4 underneath the 'g' panel
- X near the bottom of the top shell
- X near the top of the top shell

[^1]: [Reddit Guide](https://www.reddit.com/r/MouseReview/comments/aksjr6/g502_switch_replacement_guide_highres/)
[^2]: [Switch Discussion](https://www.reddit.com/r/MouseReview/comments/15553x6/omron_d2f01f_switches_still_considered_the_best/)
