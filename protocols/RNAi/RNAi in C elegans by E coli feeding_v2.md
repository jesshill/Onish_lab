# RNA interference in C. elegans by _E. coli_ feeding (V2)

**Prepared by:** 

**Date:** 

---

### PURPOSE: 
RNA interference, or RNAi, is a technique in which double stranded RNA is introduced to an organism, resulting in targeted gene silencing (knock down). We can induce RNAi in C. elegans by first preparing plates with E. coli that express target gene dsRNA, which the worms will eat. Then, 4th larval stage worms are transferred to the RNAi plates and allowed to lay eggs. At the desired stage of development the progeny are collected and scored for phenotypes.

dsRNA enters C. elegans tissue once ingested. Inside the cell, the enzyme Dicer cleaves the double stranded RNA into short interfering RNA, or siRNA, which is between 21 and 23 nucleotides long. Next, the siRNA associates with the RNA induced silencing complex, also known as "RISC", and becomes unwound. Then, the siRNA/RISC complex binds the target mRNA via complementary base pairing. This leads to the degradation of the mRNA, thereby knocking down that gene.

RNAi feeding libraries use the E. coli strain HT115 (DE3), which contains an isopropyl beta-D-1-thigalactopyranoside (IPTG)-inducible T7 polymerase site to promote the production of double-stranded RNA (dsRNA). 


*This protocol allows the user to knock down the expression of a given gene target in C. elegans. E. coli containing a specific expression vector can be induced to transcribe a genetic fragment from both the 5’ and 3’ ends. When the resulting double-stranded RNA molecule is ingested by C. elegans, an RNA interference reaction targets endogenous transcripts of the same sequence for destruction. In this protocol, the method of testing embryonic lethality (% hatching) is described but observations can also be made in the parent as well.  The effects of the RNAi are then observed with smFISH.


### CONTROLS:
- Positive control:
  - _pop-1_ RNAi is a standard positive control that should produce 100% embryonic lethality.
- Negative control:
  - Empty vector (L4440) is a common negative control that should result in a 0 % embryonic lethality.
- Question specific controls:
  - Other controls can be selected for the exact question of interest. For example, the researcher is interested in embryonic lethality due to intestine-specific failure, _elt-2_ RNAi (intestine regulatory gene) is a typical control.

### REAGENTS:
<ins> Carbenicillin stock solution [100 mg/mL] <ins>
- Combine the following reagents into a 15 mL conical tube:
  - 1 g Carbenicillin
  - 10 mL H2O
- Filter sterilize the solution through a 0.22 um filter.
- Make 1 mL aliquots.
- Clearly label, date, and then store at -20C. 
- Can use in a concentration range of 25 - 100 ug/mL.
  - Suggested final concentration is 100 ug/mL.

<ins> IPTG stock solution [1 M] <ins>
- Combine the following reagents into a 15 mL conical tube:
  - 2.38 g Isopropyl-β-D-thiogalactopyranoside (IPTG)
  - 10 mL H2O
- Filter sterilize solution through a 0.22 um filter.
- Make 1 mL aliquots.
- Clearly label, date, and then store at -20C.
- Can use in a concentration range of 0.1–2 mM.
  - Suggested final concentration is 1 mM. 

### PLATE PREPERATION: 

<ins> NGM+Carb+IPTG Plates (1000 mL) <ins>

- Mix the following reagents:
  - 3 g NaCl
  - 2.5 g Bacto Peptone
  - 17 g Bacto Agar
  - Add water to 975 mL
- Add a stir bar   
- Autoclave for 40 minutes to sterilize
- Cool media to about 50 – 65C.
- Using sterile technique, add:
  - 0.5 mL 5 mg/mL Cholesterol
  - 0.5 mL 1 M CaCl2
  - 0.5 mL 1 M MgSO4
  - 12.5 mL 1 M Potassium Phosphate Solution (pH 6)
  - 1 mL 100 mg/mL Carbenicillin
  - 1 mL 1 M IPTG
- Once all ingredients have been added, stir media thoroughly and then pour plates.
- Store plates at 4C for about a month. 

### BACTERIAL PREPERATION: 

...

### PROTOCOL:

1. Obtain _E. coli_ RNAi feeding strains

- Streak out strains from the _E. coli_ feeding collection onto LB Carb [100 ug/mL] plates. Grow at 37C over night.
- Store resulting single colonies in a personal -80C stock for future reference.
- Sequence the resulting vectors to ensure the appropriate transcript will be targeted.
- Stock plates of _E. coli_ can be stored at 4C for 4–6 wk after which time, a fresh batch from the -80C is recommended for best dsRNA activity.

2. Grow and Induce _E. coli_

<ins> DAY 1 <ins>

- Inoculate 5 mL of liquid LB Carb [100 ug/mL] with each _E. coli_ strain. Repeat for all strains needed, including controls.
- Grow overnight at 37 C, shaking (200 RPM).

<ins> DAY 2 <ins>

- No more than 18 hr after initial _E. coli_ inoculation dilute overnight cultures. Add 40 uL of each overnight culture into 6 mL fresh LB Carb [100 ug/mL].
- Grow shaking at 37C for 3 hours.                      
- Induce dsRNA transcription by adding IPTG to 1 mM final concentration to each culture.
- Organize 6 cm RNAi plates by labeling them.
- Add IPTG to 1 mM final concentration per plate (use calculation above).
- 3 hours after _E. coli_ induction, plate 500 ul of each culture on a 6 cm RNAi plate.
- Let plates dry overnight at room temp.

<ins> DAY 3 <ins>

\*Store plates up to 2 weeks at 4 C or use immediately in step 3.

3. Move worms onto _E. coli_ seeded plates

<ins> DAY 3 or LATER <ins>

- Move 1 – 2 worms onto an _E. coli_ seeded plate. L4 worms can be used or very young adult worms.
- This step can be optimized in a variety of ways. N2 worms or RNAi sensitive worms can be used. The age of the worm can be optimized for each transcript. Just try to stay consistent with the age of each worm added within a given experiment.
- Allow worms to grow on plates for 24 hours at 20 C.

4. Capture laid eggs

<ins> DAY 4 <ins>

- 24 hours after first _E. coli_ exposure, obtain freshly laid eggs by moving worms to a new _E. coli_\-seeded plate (of the same dsRNA expression). This is called the “24 hr. Capture Plate”.
- Let the worms lay on the capture plate for 2 hrs – 24 hours depending on their egg-laying rate. Try to capture at least 50 eggs.
- Move worms to a new plate (of the same dsRNA type) and return to 20 C. Count the eggs on the capture plate.

5. Measure embryonic viability.

<ins> DAY 5 <ins>

- 24 hours after the adult worms were moved off of the capture plate, count the # embryos and # hatched worms.
- Compare the total numbers with the number embryos counted the day before.
- If there are discrepancies, look for dead worms on the lip of the plate and try to count those.
- If counting is challenging, count each plate twice.
- Tabulate numbers both 1) by hand in the lab notebook and 2) in excel spreadsheet form.
- Calculate the % viability and % lethality for each strain.

<ins> 48 – hour time point <ins>

- In addition, a 48 hour time point is often useful. Start another capture plate for 48 hours after first _E. coli_ exposure and repeat the embryonic viability calculation.


### REFERENCES:

JoVE Science Education Database. Biology I: yeast, Drosophila and C. elegans. RNAi in C. elegans. JoVE, Cambridge, MA, (2023).

...

---

UPDATES TO THE PROTOCOL:

Hi Erin,


The few changes to the original protocol were made from recommendations from the Ahringer lab’s currect protocol. The main differences are some concentrations and choices of antibiotic. The major change is the top spreading of Carb/IPTG; also IPTG is not added to liquid culture.

1.       Grow E.coli in 100 mg/L Carb LB liquid overnight.

2.       Inoculate 6 mL fresh LB-Carb with 40 ul of overnight culture.

3.       Grow fresh LB Carb for 6 hours shaking at 37C

4.       Top spread NGM plates with 100 mg/L Carb and 1 M IPTG. I premix 1:1 solution of our Carb and IPTG stocks then pipette 1ul Carb-IPTG mix per 1 ml medium. Assuming 6 cm plates are 12.5 mL and 10 cm plates at 25 mL total. Spread with the L-shaped glass pipette, with ethanol/flaming in between.

5.       Briefly let the 25-50 uL of topspread Carb-IPTG mix soak in.

6.       Seed plates with 500-1000 ul 6 hour culture.

7.       Allow plates to dry and induce overnight.

8.       Store at 4 degrees.



Jay
