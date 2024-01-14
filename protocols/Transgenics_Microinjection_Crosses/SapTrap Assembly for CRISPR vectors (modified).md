**SapTrap Assembly for CRISPR vectors**

Note: this protocol is adapted from Schwartz and Jorgensen 2016, transformation protocol adapted from Alisa Shaw

---

REAGENTS/MATERIALS: 

Day 1:

- 50nM IDT-synthesized oligonucleotide (gRNA donor or HR template donor)
  - Resuspended with DEPC H20
- 50nM Target plasmid (for gRNA – pMLS134; for HR template – pMLS257)
- SapTrap Enzyme Mix:


Day 2:

- Restriction enzyme for counter-selection of vector
  - For pMLS134, we can use: BamHI, BanII, StyI, BtgI, NcoI
  - For pMLS257, we can use: BamHI, StyI, NcoI, StuI, NdeI, XcmI, SpeI
  - Prior to counter-selection, ensure your desired insert does not contain the restriction site you’ll use for counter-selection. 
- Purified pUC19 plasmid as a transformation control
- Heat-shock competent cells (Top10 or DH5alpha)
- LB 
- LB agar plates with selective antibiotic

Day 3/4: 

- Selective antibiotic stock
- Primers for insert verification 
- PCR reagents

NOTES:

- For the oligonucleotide synthesis, NEB reports that SapI has similar cutting efficiency towards the end of DNA templates. However, if cloning is low efficiency it would be good to try and add a few bp to each end of the DNA template. For DNA templates in the future, it will be beneficial to just design them with a few extra bases on each end just to be safe 
- NOTE: For each transformation we need 50uL of competent cells. Dylan made cells in 100uL aliquots, so I usually double the amount of DNA I add to my cells to ensure good transformations. For SapTrap, I add 2uL of each SapTrap reaction

PROCEDURE:

Day 1:

Donor Fragment Preparation: 

For gBlocks gene fragments (Typically used for HR templates):

- Centrifuge tube with dried gBlock at 3000xg to settle, resuspend in TE buffer or nuclease-free H2O (pH 7.5-8) to reach 50nM. Use the equation below for the calculation. The molecular weight of the oligo should be reported on the specification sheet (I assumed they followed the convention of reporting molecular weight in g/mol because IDT doesn’t directly report units). Note that the amount delivered is typically in ng, so we need to input that unit conversion (1ng = 1\*10^-9g)

Resuspension volumeuLfor 50nM= amount g-block delivered (g)\*106uL50\*10-9M\*oligoMWg/mol

\*calculation example – for a g-block with a molecular weight of 137020.9 that I received 250ng of, I find that I need to resuspend in 36.49uL for 50nM

- IF they give you a delivery amount in mol:

Resuspension volumeuLfor 50nM= amount g-block delivered mol\*10650\*10-9

\*calculation example – for a g-block that I received 1824fmol of, I find that I need to resuspend in 36.49uL for 50nM

For dsDNA oligos (Typically used for gRNAs):

- Ok so for this we’ll have to do serial dilutions since we just get in so much of each duplex.
- I’ll start by making a 100uM dilution of the duplex stock: (note that typically IDT reports delivery in nmol, and 1 nmol = 1\*10^-9mol

Resuspension volumeuLfor 100uM= amount duplex delivered mol\*106100\*10-6

\*calculation example – for a duplex that I received 250ng of, I find that I need to resuspend in 890uL for 100uM

- We’ll then take 0.5uL of the 100uM duplex solution, and dilute it with 999.5uL ddH2O (yes) to reach a final [] of 50nM

SapTrap Assembly:

- Combine and mix by pipetting:
  - 1uL of 50nM destination plasmid 
  - 1uL of 50nM donor fragment 
  - 3uL ddH2O
- Thaw a 2uL aliquot of SapTrap Enzyme Mix (see above for recipe) 
- Add 0.5uL of DNA mixture to the 2uL SapTrap Enzyme Mix
- Thoroughly mix, incubate the reaction overnight in thermomixer or on bench at 25C 

Day 2:

- The next day, heat inactivate T4 ligase by incubating at 65C in thermomixer for 30min 
- After T4 ligase inactivation, prepare a mix of 1xCutSmart + 1-2U/uL of counter-selection restriction enzyme (for pMLS257 or pMLS134 I usually use BamHI)
- Add 2.5uL of counter-selection restriction enzyme solution to the SapTrap mix and incubate at 37C for 1h (thermocycler).
- While waiting for your counter-selection, warm up all the materials needed for transformation.


Heat-shock Bacterial Transformation:

- You need to first warm up:
  - LB (to room temperature)
  - Bead bath (to 42C)
  - Incubator (to 37C)
  - LB agar plates with proper antibiotic selection (place in 37C incubator). For each transformant we will use 2 plates.
- Once your counter-selection mix has sat for 1h at 37C, retrieve a 100uL aliquot (see notes) of competent cells from the -80C freezer and place on ice.
- After just a few minutes, the cells should be gooey and cloudy, but not totally liquid. At this point we will add 2uL of our SapTrap reaction to the cells, and tap gently on the benchtop to mix (no pipette mixing). 
- As a control, add 2uL of 10pg/uL pUC19 to a separate tube of competent cells as a positive transformation control.
- Allow cells to sit with DNA for 30min in ice. 
- After 30min, place cells in the 42C bead bath for exactly 30s. Immediately take out and return to ice. Allow to sit for ~1min
- Add 500uL room temperature LB to the cells (If using 50uL cells, use 250uL LB).
- Shake cells in 37C incubator at 225rpm for 1h.
- For each transformant, streak 2 LB plates with selective antibiotic – one with 50uL of bacteria and one with 200uL bacteria. Parafilm and grow these plates at 37C overnight. 













Day 3: 

Picking/Growing Colonies

- Prepare PCR tubes with 10uL ddH2O for how many colonies you plan to pick
- Using pipette tips, pick one colony into each PCR tube. Vortex briefly. We will use 7uL to inoculate overnight cultures and 3uL to do colony PCR.
- Take 7uL of each culture and inoculate overnight cultures with 4mL LB and 4uL 1000X antibiotic. Ensure that you also grow a positive (pUC19 transformed) and negative (OP50) control
- For your remaining 3uL of bacteria, boil PCR tubes to lyse bacterial cells with this program: 
  - 2uL Volume
  - 95C – 5:00min
  - 12C – hold (infinite)

Colony PCR

- For PCR verification of HR template inserts, we can use the primers oSG015 (FWD) and oSG016 (REV)
- For gRNA inserts, we need to use primers specific for the target sequence, because with pSG017 and pSG018, the amplicon size will be about the same size regardless of if insertion occurred.

- My general scheme for PCR is pretty simple. For each sample (~3uL of bacteria resuspended in ddH2O) I use 45uL of the mix in the table below. The only variable is which primers you decide to add. Ensure to keep polymerase on ice and minimize the time it is out of the -20C freezer

- I like to make all the mixes first, and then add 45uL of each mix to the sample. 

- Make sure to consider the positive/negative control – I use 1uL of 50ng/uL of naked template (pMLS134 and pMLS257).

Samples (Fill out the tables in excel for each plasmid and primer set you plan to use: 

|Plasmids  |Primers  |Mix |
| :- | :- | :- |
|Some HR template plasmid|pSG015 and pSG016|Mix 1|



Mixes: 

|Mix 1 |Mix amount for 1 sample (uL) |Mix amount for X samples|
| :- | -: | -: |
|# of samples for this mix|1||
|H2O|33 |(=x\*33)|
|5X Q5 Rxn buffer  |10 ||
|10mM dNTP |1 ||
|100uM Primer 1 |0\.25 ||
|100uM Primer 1 |0\.25 ||
|Q5 Taq polymerase (add last)|0\.5 ||
|Total |45 ||
Once the mixes are made and added to the DNA, I use the following thermocycler protocol (listed as (Q5) in thermocycler).

- 98C 30sec  
  - Cycle:
  - 98C 10sec  
  - 65C 30sec  
  - 72C 10min 
  - 30X cycles  
- 72C 2min  
- 12C hold  



