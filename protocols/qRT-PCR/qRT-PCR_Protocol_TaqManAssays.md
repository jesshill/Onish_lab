## cDNA synthesis and qRT-PCR with TaqMan Gene Expression Assays

**Date:**

**Author:**

---

### Invitrogen SuperScript™ IV First-Strand Synthesis System

Add max amount of RNA the kit takes if we get it. Try to add same amounts of RNA for each/normalize input amount of RNA. **Aim for 500 ng.**

Example:

PA14: 500 ng×uL297 ng=1.68 uL 

**SuperScript™ IV First-Strand cDNA Synthesis Reaction**

The example procedure below shows appropriate volumes for a single 20-μL reverse transcription reaction. For multiple reactions, prepare a master mix of components common to all reactions to minimize pipetting error, then dispense appropriate volumes into each reaction tube prior to adding annealed template RNA and primers.

1. Anneal primer to template RNA
- Combine the following components in a PCR reaction tube.
   - Note: Consider the volumes for all components listed in steps 1 and 2 to determine the correct amount of water required to reach your final reaction volume.

|Component|Volume|
| :- | :- |
|50 μM Oligo d(T)20 primer|1 uL|
|10 mM dNTP mix (10 mM each) |1 uL|
|Template RNA (10 pg–5 μg total RNA or 10 pg–**500 ng** mRNA) |Up to 11 μL|
|DEPC-treated water |Up to 13 μL|

- Mix and briefly centrifuge the components.
- Heat the RNA-primer mix at 65°C for 5 minutes, and then incubate on ice for at least 1 minute.
2. Prepare RT reaction mix
- Vortex and briefly centrifuge the 5× SSIV Buffer.
- Combine the following components in a reaction tube.

|Component|Volume|
| :- | :- |
|5× SSIV Buffer|4 uL|
|100 mM DTT |1 uL|
|Ribonuclease Inhibitor |1 μL|
|SuperScript™ IV Reverse Transcriptase (200 U/μL|1 μL|

- Cap the tube, mix, and then briefly centrifuge the contents.
3. Combine annealed RNA and RT reaction mix
- Add RT reaction mix to the annealed RNA. 
4. Incubate reactions
- Incubate the combined reaction mixture at 50–55°C for 10 minutes.
   - We did 52C. 
- Inactivate the reaction by incubating it at 80°C for 10 minutes.
5. PCR amplification 
- Use your RT reaction immediately for PCR amplification or store it at –20°C.
   - Note: As a recommended starting point for PCR, reverse transcription reaction (cDNA) should compose 10% of the total reaction volume

--

**PCR Amplification and Detection: TaqMan® Gene Expression Assays—single–tube assays, Pub. No. 4401212 Rev. D**

1. Before you begin (60X assays ONLY): Dilute 60X assays to 20X working stocks with TE, pH 8.0, then divide the solutions into smaller aliquots to minimize freeze-thaw cycles. The size of the aliquots depends upon the number of PCR reactions you typically run. An example dilution is shown in the following table.
   1. Gently vortex the tube of 60X assay, then centrifuge briefly to spin down the contents and eliminate air bubbles.
   1. In a 1.5-mL microcentrifuge tube, dilute sufficient amounts of 60X assay for the required number of reactions.
   1. Some Gene Expression Assays come pre-diluted (in the 20X format)!
      1. Can aliquot the 20X assays, and store at -20C until use.  

|Component|Volume|
| :- | :- |
|TaqMan® Gene Expression Assays (60X)|40 uL|
|TE, pH 8.0 (1X)|80 uL|
|Total aliquot volume|120 uL |

1. Store aliquots at -20C until use. 
1. Prepare the PCR reaction mix - Thaw the cDNA samples on ice. Resuspend the cDNA samples by inverting the tube, then gently vortexing. 
   1. Mix the Master Mix thoroughly but gently 
   1. Combine the PCR Reaction Mix and assays in an appropriately sized microcentrifuge tube according to the following table.

|Component|Volume for 1 reaction in 96 well plate|
| :- | :- |
|Master Mix (2X)|10 uL|
|<p>TaqMan® Gene Expression Assay</p><p>(20X)</p>|1 uL (singlplex), 2 uL (duplex) |
|Nuclease-free water|7 uL (singleplex), 6 uL (duplex) |
|Total PCR reaction mix volume |18 uL|

Each TaqMan Gene expression assay (probe, F and R primers) is provided in a preformulated 20X mix; 1X final concentrations are 250 nM for the probe and 900 nM for each primer.

1. Vortex the PCR Reaction Mix, then centrifuge briefly.
1. Transfer the appropriate volume of PCR Reaction Mix to each well of an optical reaction plate.
1. Add cDNA template (1 pg–100 ng in nuclease-free water), or nuclease-free water for NTC, to each well.
   1. Assume a 1:1 ratio of RNA converted to cDNA
   1. 2 μL for a 96-well plate 
   1. Note: Be sure to adjust the volume of nuclease-free water in the PCR reaction mix for a larger volume of cDNA.
   1. IMPORTANT! For optimal results when using TaqMan® Fast Universal PCR Master Mix, no AmpErase™ UNG, prepare the plate on ice. Run the plate within 2 hours of preparation, or store the plate at 2–8°C for up to 24 hours.
1. Seal the plate with a MicroAmp™ Optical Adhesive Film, then vortex briefly to mix the contents.
1. Centrifuge the plate briefly to collect the contents at the bottom of the wells.
1. Set up and run the real-time PCR instrument: Bio-Rad CFX96 System 

||UNG activation|Polymerase activation|PCR (40 cycles)|PCR (40 cycles)|
| :- | :- | :- | :- | :- |
||Hold|Hold|Denature|Anneal/extend|
|Temperature|50C|95C|95C|60C|
|Time (min:sec)|2:00|0:20|0:03|0:30|

1. Run the PCR reaction plate
   1. Load the reaction plate into the instrument and start the run. See your instrument’s user manual for detailed instructions on how to load and run the plate.
1. (Optional) Wipe down a gel box and gel caster with RNase inhibitor solution. Pour a ‘1% Agarose/Gel red’ gel and set aside to cool. 
1. Analyze the results. 
   1. Data analysis varies depending on the instrument. See the TaqMan® Fast Advanced Master Mix Protocol (PN 4444605) and your instrument’s user manual for detailed instructions on how to analyze the data.
      1. For detailed information about data analysis, see the appropriate documentation for your instrument. 
   1. Use the absolute or **relative quantification (ΔΔCt)** methods to analyze results. The general guidelines for analysis include:
      1. View the amplification plot; then, if needed:
         1. Adjust the baseline and threshold values.
         1. Remove outliers from the analysis.
      1. In the well table or results table, view the Ct values for each well and for each replicate group.
