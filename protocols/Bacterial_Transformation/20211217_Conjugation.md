## General Conjugation Protocol (Barrick Lab)

Conjugation is a reliable, robust method to transfer plasmids between bacteria. This is a general purpose protocol for conjugation using a DAP (diaminopimelic acid, 0.3 mM) auxotrophic donor strain with a standard strain. Many steps can be optimized, but this is a good starting point for trying conjugation to a new strain. For additional resources, concerns, and options, see the end of this document. For extra information on tri-parental conjugations, see the end of this document.

### Required:

- **Donor strain** that contains your plasmid of interest (this should be a strain like Mu Free Donor (MFDpir) or B2155, which contain integrated rp4-based transfer machinery). MFDpir can be requested from [its creators](https://research.pasteur.fr/en/tool/genetic-methods-and-tools/). Your plasmid should contain an oriT sequence (known as the origin of transfer, this allows it to be transferred)
- **Recipient strain**
- **Growth media** for each individual strain.
- **Non-selective plates** containing **DAP** (0.3 mM) for conjugation. These plates should be made from media that **both** strains can grow on, and contain no antibiotic. You can set up ~4 conjugation mixtures per plate.
- **Selective plates**. These plates should contain the same antibiotic as the marker on the plasmid you want to transfer, but no DAP. To plate dilutions, you need 3-4 plates per conjugation mixture. You may also include additional counter selectable markers (i.e., antibiotics your recipient is resistant to but the E. coli donor is not) to minimize E. coli background.
- **Non-selective** plates (optional). If desired, these can be used to determine the conjugation efficiency by comparing growth to the selective plates.
- Standard pipettes, microcentrifuge tubes, and incubator that supports growth of both strains.

### Protocol:

1. Grow overnight cultures of your donor and recipient strains. Donor strain must be grown in the presence of DAP (0.3 mM) and appropriate antibiotic.
1. Gently spin down 1 mL culture (~3000 rpm for 5 minutes) and wash donor and recipient cells in PBS. Repeat. Resuspend in 500 µL PBS. This removes residual antibiotic from the donor cell culture. Recipient cells can also be scraped off of plates and washed in PBS to prepare for conjugation.
1. Measure optical density and combine 1:1 ratio of donor and recipient cells in micro centrifuge tube (50 µL : 50 µL). Mix by pipetting twice. For particularly slow growing strains that will be outcompeted rapidly by E. coli, a larger recipient:donor ratio will yield more transconjugants (see notes).
1. Plate 100 µL of mixture onto non-selective plate containing DAP. Do not spread. You can plate up to 4-5 conjugations on the same plate by carefully plating into quadrants on the plate (See image 1 for example of 5 conjugations on the same plate).
1. Incubate conjugation plate overnight (See image 2 for example of overnight growth).
1. Scrape up each conjugation mixture into a micro centrifuge tube with 1 mL PBS. Vortex and gently spin down. Repeat.
1. Resuspend conjugation mixture in 1 mL of PBS. Plate 100 µL of this mixture and 100 µL of a 10-fold dilution onto selective plates.
1. Pick single colonies and restreak or grown in selective media. Confirm transfer of the plasmid via PCR amplification of the insert.

 ![image](https://github.com/jesshill/Onish_lab/assets/41451575/a10cab67-ccfc-487a-bb66-c1014bff8cac)

 ![image](https://github.com/jesshill/Onish_lab/assets/41451575/28ca8e93-959e-48fe-ac6f-19d8c9cedf9d)


### Considerations and customization:

Many aspects of this protocol can be tweaked if your initial conjugation attempts are unsuccessful.

1. **Relative amount of recipients : donor**. You may see increased conjugation efficiency with an excess of recipient or excess of donor. Some strains do much better with ratios of 10:1 between either species, for some a ratio of even 100:1 works best.
1. **Conjugation time**. Robust lab strains of E. coli can be conjugated into in less than hour, while other non-model organisms may require 24+ hours. If doing a short conjugation time, the mixture can be plated onto sterile filters instead of the agar plate itself. You can pick this filter up and put directly in PBS. Vortex to release transconjugants.
1. **Antibiotic concentrations**. Many non-model organisms require substantially less antibiotic for effective selection than common lab strains. For starting in a new strain, I recommend a series of plates with different antibiotic concentrations for selection. If using low strength ampicillin for selection, plate 20 µL of the conjugation mixture and spread using standard microbiological practice. Colonies isolated from low dose ampicillin plates will have to be restruck to confirm resistance.
1. **Conjugation mixture stocks**. You can freeze conjugation mixtures with glycerol to make stocks that will allow you to test multiple selective amounts over time. This is risky, however, and only works for relatively high efficiency conjugations.

### Notes on tri-parental conjugation:
Tri-parental conjugation is required by some protocols, such as mini-Tn7 integration (<https://www.nature.com/articles/nprot.2006.24>). Mini-Tn7 integration requires delivery of two plasmids into the recipient - a primary plasmid that encodes the mini-Tn7T transposon and a helper plasmid that encodes the TnsABCD transposase subunits. For tri-parental conjugation, you need to combine a set ratio of the three strains - your two donors and your recipient. An example for calculating a 1:1:1 ratio is given below. As in other conjugations, modifying this ratio to include more or less of the recipient may result in more successful conjugations and integrations.

1. Measure the OD600 of the overnight culture from each strain.
   Donor #1 : 2.58
   Donor #2 : 1.89
   Recipient : 2.02
1. Calculate how much of each culture to add for a 1:1:1 ratio and a 100 µL pool.

   ((1.89 / 2.58) + (1.89 / 1.89) + (1.89 / 2.02)) x X = 100 µL

   X = 37.47 µL

   (1.89 / 2.58) x 37.47 µL = 27.44 µL donor #1

   (1.89 / 1.89) x 37.47 µL = 37.47 µL donor #2

   (1.89 / 2.02) x 37.47 µL = 35.05 µL recipient
   
1. Proceed as normal for regular conjugations.

### Contributors to this protocol:
- Sean Leonard
- Julie Perreau


