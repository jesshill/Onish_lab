# Keyence protocols for Jess 

**Date:** 11-10-2020

**Author:** Izabella M. 

--- 

## Making Glass Needles for Dissections and Mouth Pipette

### Pulling glass needles

- on switch of micropipette pliers = left side
- capillary tubes in bottle by machine
- use program #76 Nish dissection (type in 76 on the screen)
- slide capillary along ridge, about halfway in up until wall of chamber and clamp down with thumb screw
- push on metal levers on both sides to unclip
  - don't want tube to knock into heating element
- use things below thumb clamp to move both sides together - must move both sides at the same time
- loosen thumb knob slightly, move capillary tube through so it's about even
- tighten both thumb screws a lot
- close shield and press start
- open shield, loosen screws, and take out needles by pulling straight up
- after making needle, cut it

### Cutting the glass needle to desired size

- power switch on front of cutter
- slide needle into holder until it doesn't come out when you pull it because rubber gasket then tighten front
- clip holder into machine holder on left
- left bottom micromanipulator below needle = up and down, left top knob = left and right
- front manipulators move machine relative to needle
- position needle next to ball
- adjust needle into view frame, then adjust machine/viewer
- each small tick = 10 um
- set to 60-70 um with outside wall of needle (use top of scale for reference) using front knobs
- bring down to touching blob
- use knob on bottom right off machine to turn up heat (all the way towards me = off)
- start with heat all the way off, push foot switch to turn on, turn up until needle starts to melt into blob just a bit
- use coarse up and down (bottom needle knob) to break it 
- repeat if necessary
- then bring it all the way up and tilt holder up and out
- unscrew top securing part and take out needle 
- turn heat all the way up to melt into broken needle

## Making Slides for Imaging Gravid Worms

### Start an hour before imaging

- TURN ON HIGH HEAT SETTING (right switch) ON WAX MELTER AND GET THAT HEATING
- get gravid ELT-2 and L4440 RNAi plates from incubator
- get glass slide with wells and make sure it is clean (use EtOH)
- get 2 microscope slides and label them with: JM149, ELT-2 or L4440 RNAi, gravid, date
- put 120 uL M9 in one well (LABEL) and 120 uL M9 + NaN3 in the other (LABEL)
- use pick to move worms off plate into M9 well (to wash them of E. coli)
- use mouth pipette with glass needle 100 um in diameter (can break gently on benchtop if the ones you have are too small) to move worms from M9 well to M9 + NaN3 well
- use mouth pipette to move worms onto center of slide in bubble of M9 + NaN3
- make sure there is enough M9 + NaN3 so there will be only minimal air bubbles
- get coverslip, gently move until at edge of bubble, drop down gently
- look at slide under microscope and make sure worms aren't too close to edge that they would get covered with valap
  - if they are, use pipette tip to gently move coverslip
- use quick swipes with cotton tip applicator to apply valap to all 4 sides, sealling the slide
- check under microscope to make sure it is fully sealed
- discard needle in sharps bin in 227B
- clean glass slide with 2 wells with EtOH into liquid waste beaker over sink
- repeat process for other RNAi strain
- clean mouth pipette into liquid waste with EtOH and water if liquid got into lower area of it, otherwise just clean mouth part with kimtech wipe and EtOH

keep M9/NaN<sub>3</sub> for about 6 months or less. Will notice when going bad because worms will become less affected/paralyzed. 

Make up 15 mL of 25 mM NaN<sub>3</sub> (FW: 65.01 g/mol; S2271-25; Fisher Chem.) in M9 

## Imaging Gravid Worms on Keyence Microscope

- get key to Keyence room from Bamburg lab; in top drawer directly to the right of the door on wooden block
- turn on light box, then microscope, then computer
- make sure slide holder is the one in the Keyence
- log into Nishimura lab area of computer - password on the computer
- open documents and create new folder for this experiment with the date and title in my folder/area
- open Keyence program, called BZ-X viewer. 
- switch to 10x objective and zoom out as much as possible
- put slide into holder (slide tray), **coverslip side down**
- zoom in, focus, find worms (10-15) and save their locations (set a point memo for each worm) 
- switch to 40x ‘Plan Apoλ NA 0.95’ lens (not fluor)
- check image settings!!
  - Resoluton/sensitivity = high resolution
  - Transmitted light = 25%
  - Aperture stop = 20%
  - GFP exposure 1/70s
  - Brightfield/Phase exposure = 1/50s
- go to worm 1's location, switch channel to just GFP, use this for fine focus
- use Z-stacks to take image: 
  - set upper bound as where the top of the worm is just out of focus
  - set lower bound as where bottom of the worm is just out of focus
  - set pitch (increments for taking images) at 1 um 
  - this should all equate to about 10 images per worm
- save image name as JM149\_gravid\_RNAiStrain\_worm\_1 in gravid folder
- repeat for all worms
- For shut down:
  - Close out of software
  - Turn off microscope
  - Turn off lightbox 

can set as many edge points as you want

## Keyence Image Stitching with Z-Stacks

### For larger worms (L3, L4, gravid) that had multiple panels of images taken initially:

- open BZ-X file (the first one in the folder with the Keyence icon on it)
- this will open the file in the analyzer
- click to **merge** on top left out of z-stacks
- deselect **overlay** (top right) and select **CH2 GFP** above image preview
- select **full focus** at bottom
- select **sectioning images**\*

using sectioning images and not normal because gets rid of haze and seems artificial and bad, want the haze because reflects full intensity at all z-stacks layers

- this loads z-stacks and displays preview from multiple images it took to capture worm
- correct shading, auto, UNCOMPRESSED (have to click this), and adjust image positions
- click **start stitching** 
- file -> export in original scale -> TIFF
- change file path to correct worm
- rename JM149\_stage\_RNAi\_worm\_#\_fullfocussectioning\_GFP\*

a shortcut for this is once you're in the right image folder, click on another image in the folder that will have the correct first part of the naming prefix, delete the random numbers and such at the end after the worm number, and paste in "fullfocussectioning\_GFP"

- exit -> don't save -> close
- open same worm's BZ-X file
- change channel to **brightfield CH4** below image
- make sure it is on **merge** tab
- scroll through z-stacks using bar on left and choose most in focus one (somewhere in the middle)
- select **load** at bottom of screen
- correct shading, auto, UNCOMPRESSED, and adjust image positions
- start stitching
- file ->export in original scale -> TIFF (not big TIFF)
- double check pathway (it should be correct)
- rename: JM149\_stage\_RNAi\_worm\_#\_stitch\_brightfield\*

can use same renaming trick as described above for this one, execpt I just typed out "stitch\_brightfield" since the other one is more annoying to type and I liked that one being the one I copied and pasted

- exit -> no -> close
- repeat for all worms
- When done:
  - Close out of software and say ‘No to all’

### For smaller worms (L1, L2) that only had one image panel taken:

- open BZ-X file (the first one in the folder with the Keyence icon on it)
- this will open the file in the analyzer
- stay in the z-stacks selected area (it should default to this)
- deselect overlay and CH4 (so only GFP/CH2 is selected)
- click load on the bottom right
- it makes a thing where you can scroll through the different z-stacks
- click full focus in the middle of the top bar
- click sectioning images 
- click on the image it produces
- click on the save icon on left of task bar just above image
- go to correct file folder for the worm you're stitching images of
- rename JM149\_stage\_RNAi\_worm\_#\_fullfocussectioning\_GFP and click save\*

a shortcut for this is once you're in the right image folder, click on another image in the folder that will have the correct first part of the naming prefix, delete the random numbers and such at the end after the worm number, and paste in "fullfocussectioning\_GFP"

- don't need to do brightfield because only 1 image panel
- repeat for all worms
- When done:
  - Close out of software and say ‘No to all’
