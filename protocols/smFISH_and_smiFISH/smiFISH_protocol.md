## smiFISH Protocol

Prepared by: Dylan Parker and Samuel Boyson on 20210302

Adapted by: Jessica Hill on 12-26-2023

---

### NEEDED REAGENTS AND SOLUTIONS

**0.44% Bleaching Solution** 
- 40 mL sterile water
- 7.2 mL 5 N NaOH
- 4.5 mL 5% NaHOCl

*only need if embryo prepping sample and trying to image embryos.

**Liquid Nitrogen**
- Fill a Dewar with liquid N<sub>2</sub>

**Wash Buffer A (10% v/v formamide)**
- Make fresh for each experiment. 
- Make up 3 mL for each sample to be hybridized. Combine reagents into a nuclease free tube and vortex to mix. 
  - 200 uL --> x3 --> 600 uL Wash Buffer A (Biosearch Technologies; Cat#: SMF-WA1-60) 
  - 0.7 mL --> x3 --> 2.1 mL DEPC water
  - 100 uL --> x3 --> 300 uL Deionized Formamide (the Deionized Formamide should be stored in -20C and thawed fresh for use!)

*In fluorescence in situ hybridization (FISH), the addition of formamide to aqueous buffers solutions of DNA enables key procedural steps—such as the prehybridization denaturation, the reannealing step and the post-hybridization stringency washes—to be carried out at lower, less harsh temperatures without compromising the overall efficiency and specificity of the hybridization.

**Wash Buffer B**
- Make sure water has been added to Wash Buffer B before use (Biosearch Technologies; Cat#: SMF-WB1-20) 

**Hybridization Buffer (10% v/v formamide)**
- Prepare 110 uL for each sample to be hybridized
- Buffer should be mixed fresh for each experiment
- For a final volume of 110 uL, mix 99 µL of Stellaris RNA FISH Hybridization Buffer (Biosearch Technologies; Cat#: SMF-HB1-10) with 11 µL Deionized Formamide. 

*Do not freeze Hybridization Buffer.

**Pre-chill Acetone and Methanol**
- Prepare 1 mL for each sample.
- Place acetone/methanol in -20C freezer. Allow to cool. 
  - If time runs out and acetone/methanol is not cool, freeze it quickly in liquid N<sub>2</sub>, allow to thaw, and then place in the -20C freezer.

**Mounting Medium**
- Original Mounting Medium (5 mL)
  - 2.5 mL of 100% glycerol
  - 25 mg of N-propyl gallate\*
  - 100 uL of 1M Tris (pH 8.0)
  - 2.4 mL of DEPC H<sub>2</sub>0
- Updated Mounting Medium (3 mL)
  - 2.5 mL of 100% glycerol
  - 100 mg of N-propyl gallate\*
  - 400 uL of 1M Tris (pH 8.0)

*Add N-propyl gallate last
- Vortex until completely dissolved.
- Minimize exposure to light (N-propyl gallate is light sensitive).
- Prepare 1 mL aliquots in dark tubes or tubes wrapped in foil.
- Store at 4°C or -20°C.
- When medium turns yellow and begins crystalizing make fresh

**smiFISH Probe Preparation**
- Primary Probes
  - Oligos are delivered in 96-well plates diluted in IDTE buffer (pH 8.0) to 100 uM
  - Prepare equimolar mixture of primary probes and dilute in 10 mM Tris (pH 8.0) made with DEPC water until you reach a concentration of 0.833 uM per probe.  
    - Use the smiFISH dilution calculator to make the equimolar mix. 

- FLAP Preparation
  - FLAPS are delivered lyophilized. Resuspend FLAP probes in TE buffer (10 mM Tris, 1 mM EDTA (pH 8.0)) to a final concentration of 50 uM. 
  - Make 3 uL aliquots and store at -20C in the dark.

- Pre anneal smiFISH and FLAP probes
  - In a PCR tube, prepare solution of:
    - 2 uL of primary probe set (Oligo mixture prepared in “Primary Probe Preparation”)
    - 1 uL 50 uM FLAP 
    - 1 uL NEBuffer 3.1 (New England Bio Labs; Cat#: B7203S)
    - 6 uL DEPC H<sub>2</sub>0
  - In thermocycler run solution prepared above at the following:
    - 1 cycle at 85 C for 3 min
    - 1 cycle at 65 C for 3 min
    - 1 cycle at 25 C for 5 min

*You can make up in advance but keep only for one week. If making in advance, rather than the day of, store annealed probes in the freezer protected from light.

--- 

### PROTOCOL

**Harvest worms**
- Grow worms until they are gravid. 
- Harvest worms by washing them off the plates with M9. Collect in a 15 mL conical tube.
- Centrifuge at 2000 x g for 1 min to pellet.
- Aspirate supernatant. Add 10 mL M9 to wash.
- Repeat wash until supernatant is clear.
- After the final wash: 
  - if you are planning to embryo prep your samples, add 10 mL of bleaching solution to the worms and nutate for ~8 minutes until embryos are released from the mothers. The adult parts should be broken into about 2 pieces but not more than that.

*This is a critical step. Don’t bleach for too long or 2-cell stage embryos will be damaged. It is also temperature dependent, so if your samples are over or under bleached, it is likely due to a difference in temperature in your lab. Adjust time accordingly.

- Quickly centrifuge sample at 2000 x g for 1 min
- Immediately remove supernatant and quench bleaching with 10 mL M9. 

*Worms should not be in bleach solution for more than 9 minutes.

- Centrifuge at 2000 x g for 1 min. 
- Wash sample again with 10 mL M9. Wash the sample for a total of two times. 
- If not embryo prepping your sample, just continue on to removing most of the supernatant (leaving ~1 mL) and transferring the sample to a microfuge tube. 

**Sample Fixation** \(this step can be optimized for your specific background strains used in imaging)
- Centrifuge sample at 2000 x g for 1 min.
- If sample is well pelleted at the bottom of the tube, remove supernatant. If sample is not well pelleted or pelleted along the length of the tube, turn the tube 180° and centrifuge again, repeating until embryos are pelleted at the bottom of the tube.
- Fix the sample by adding 1 mL of -20°C methanol. Then vortex to break up the sample.
- Immediately submerge the sample into liquid nitrogen for exactly 1 minute.
- Remove sample from liquid nitrogen and place in -20°C freezer for ~4 min. Then centrifuge sample (2000 x g for 1 min) and remove methanol. 
  - Don’t exceed 5 min in methanol. 
- Resuspend sample in 1 mL of -20°C acetone and vortex. Then incubate for ~4 min in the -20°C freezer. Following incubation, centrifuge (2000 x g for 1 min) and aspirate off acetone. 
  - Don’t exceed 5 min in acetone. 
- Now prehybridize sample in 1 mL Wash Buffer A. Vortex sample to bring out of the pellet. 

**Hybridize smiFISH probes**
- Prepare 110 uL of hybridization solution for sample. 
- Add 2 uL of annealed smiFISH probes to hybridization solution. Vortex well, it is viscous.
  - If probing for more than 1 transcript, just add the additional 2 uL of probes to the hybridization solution. 

*Treat annealed smiFISH probes as diluted smFISH probes. 2 uL of annealed smiFISH probes work well for most hybridizations.

*smiFISH probes can be used in combination with traditional smFISH probes.

- Centrifuge sample (2000 x g for 1 min) and aspirate off Wash A buffer.
- Add 100 uL hybridization solution containing probes to the pelleted sample. 
- Hybridize overnight at 37°C in the dark while shaking (450 rpm). 
  - If need to leave samples for longer, up to 3 days of hybridization still works. 

**Wash and Image**
- Next day, add 1 mL of Wash Buffer A directly to the hybridized sample. 
- Incubate at 37°C for 30 min with shaking (450 rpm). 
- Centrifuge sample (2000 x g for 1 min) and aspirate supernatant.
- Add 1 mL of Wash Buffer A + 2 uL of 5 mg/mL DAPI solution to sample.
- Incubate at 37°C for 30 min with shaking (450 rpm).
- Centrifuge sample (2000 x g for 1 min) and aspirate supernatant.
- Add 1 mL of Wash Buffer B to sample and vortex. Incubate for 5 min at 37°C with shaking (450 rpm).
- Centrifuge sample (2000 x g for 1 min) and aspirate supernatant.
- Resuspend sample in 50 uL of mounting medium (or less depending on your sample density). Let the sample sit (protected from light) for between 10 – 30 min before moving on, to let the antifade permeate the cells. Can sit out at room temp. 
  - NEED to incubate for 30 min when using the 670 fluor.

**Mount on slides**
- Working at a dissecting scope, drop 2 – 6 uL of sample in mounting medium onto a single 8 mm 1.5 thickness round cover glass (Electron Microscopy Sciences, Cat#: 72296-08).
- Add the same volume of VectaShield Diamond anti-fade solution and pipette up and down to mix thoroughly. 
- After pipette mixing, draw off the same volume of VectaShield/sample that was just added. 
- Place a 1.5 thickness 22 mm x 22 mm square coverglass on top trying to avoid bubbles. 

*I do all of this atop a slide so that I can flip the coverglass sandwich over without getting it stuck to the microscope stage.

- Remove as much liquid as possible from between the two cover glasses using a kimwipe placed up against the round one. The aim is to flatten the sample as much as possible without damaging the embryos/worms. 

*I will often press lightly with a pipette tip at the end to squeeze out that last little bit.

- Affix the coverglass sandwich to a microscope slide using a Grace Bio-Lab Press-To-Seal silicon isolator (Sigma Aldrich; cat#: GBL664504-25ea) such that the sample will be imaged through the square coverglass.
- Head off to the microscope! 
- Store any un-imaged samples in the dark. Image same day.

--- 

### REFERNCES

Shaffer, SM, Wu, MT, Levesque, MJ, Raj, A. 2013. Turbo FISH: A Method for Rapid Single Molecule RNA FISH. PLoS One. DOI: 10.1371/journal.pone.0075120 <http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0075120>

Ji, N and van Oudenaarden, A. 2012. Single molecule fluorescent *in situ* hybridization (smFISH) of *C. elegans* worms and embryos. Wormbook. <http://www.wormbook.org/chapters/www_smFISH/smFISH.html>

Stellaris. <https://biosearchassets.blob.core.windows.net/assets/bti_custom_stellaris_celegans_protocol.pdf>

Dustin Updike

Arjun Raj

Nikolay Tsanov, Aubin Samacoits, Racha Chouaib, Abdel-Meneem Traboulsi, Thierry Gostan, Christian Weber, Christophe Zimmer, Kazem Zibara, Thomas Walter, Marion Peter, Edouard Bertrand, Florian Mueller; smiFISH and FISH-quant – a flexible single RNA detection approach with super-resolution capability, *Nucleic Acids Research*, Volume 44, Issue 22, 15 December 2016, Pages e165, <https://doi.org/10.1093/nar/gkw784>

Oligostan: Nikolay Tsanov N, Samacoits A, Chouaib R, Traboulsi AM, Gostan T, Weber C, Zimmer C, Zibara K, Walter T, Marion P, Bertrand E, Mueller F. smiFISH and FISH-quant - a flexible single RNA detection approach with super-resolution capability. Nucleic Acids Research. (https://github.com/jesshill/Onish_lab/assets/41451575/1160f999-933b-47a4-b04b-7d3ae2d6c7fa)

