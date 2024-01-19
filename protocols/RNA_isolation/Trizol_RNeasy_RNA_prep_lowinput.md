## Erin’s Trizol/RNeasy total RNA Prep Protocol - *Low Input Version*

**Date:** 07-28-2014

**Author:** Erin Nishimura 

--- 

### PURPOSE:
This protocol produces total RNA from low quantities of input tissue ranging from 10 cells – 100 mg.  For quantities less than 10 cells, the Invitrogen Cells Direct kit is preferable because it is a one-tube protocol.  Resulting RNA is suitable for producing cDNA.  It is great for RNA-seq and qRT-PCR.  This is basically a scaled down version of the canonical Trizol/RNeasy total RNA Prep (50 mg – 5 g).

### STARTING MATERIAL: 
Cells, laser captured tissue, or small quantities of dissected tissue can be used.   I’m guessing the optimal range for this process is 10 cells – 100 mg tissue.  Material should be frozen in 10 µl – 250 µl Trizol at -80C and can be stored for quite a long time (years).

### CAUTION: 
Use gloves.  Trizol requires hazardous disposal and should be handled in the hood.  It contains phenol so use caution.

---

### PROTOCOL
- Wipe down the bench, centrifuge and pipets with an RNase inhibitor.
- Gather samples.
- *Optional Step:* Homogenization and Lysis.  If cells are already homogenized and lysed, skip this step and simply thaw samples.  If samples are not lysed or homogenized, perform 1 - 3 freeze/thaw/vortex cycles.  To do so, place tubes at 37 C for 30 sec or until thawed, then vortex, then place in -80 C liquid nitrogen for 30 sec, or until frozen.  For isolated cells, do this once.  For dissected tissues, perform 3 times.
- Ensure that samples are thoroughly homogenized by viewing the sample under a dissecting microscope (looking within the epitube). If there are chunks, try vortexing or pipeting up and down.
- Bring the volume of Trizol up to a total of 500 µl.  If you have multiple samples that must be pooled, do it now.
- Add 100 µl of chloroform to samples.
- Shake tubes by hand 20 sec.  Incubate at RT, 2 – 3 minutes.
- Separate phases by spinning > 10,000 x g, 18 min, 4 C.
- Remove the aqueous phase (should be top, clear layer).  Don’t be greedy!  Leave that interface alone.
- Add an equal volume 100% EtOH.  Load prep onto a Qiagen RNeasy Mini Spin Column.
- Adhere RNA to the column by spinning > 8,000 x g, 30 sec.
- Add 350 μl RW1 to wash.  Spin > 8,000 x g, 15 sec.
- On Column DNaseI Digestion:
  - Mix 10 μl DNaseI stock to 70 μl RDD buffer for each sample.
  - Add 80 μl DNaseI/RDD to each column.
  - Incubate at RT, 15 min.
- Add 350 μl RW1 to wash.  Spin  > 8,000 x g , 15 sec.
- Place column in a new collection tube.  (Make sure RPE contains added EtOH.)  Wash column by adding 500 μl RPE.  Spin >8,000 x g, 30 sec.
- Wash again by adding 500 μl RPE.  Spin > 8,000 x g, **2 minutes**.
- Dump flow through and spin an additional 1 min.
- Place column in a fresh centrifuge collection tube. Add 30 – 50 μl RNase-free water if using the RNeasy Mini Columns and 14 ul if using the Micro Columns.  Spin > 8,000 x g, 1 min.  Use in downstream protocols as soon as possible!

### NOTES:
- *Fancy stuff:* Consider using filter-tipped pipets and low-retention tubes for this protocol.  
- *Quantification:*  Depending on the input, this protocol can yield 10 pg – 1 ug total RNA.  Quantification using the nanodrop or qubit is not recommended because it is usually just at or below the limits for accurate detection.  If quantification is required, consider using 1 – 5 µl in a qRT-PCR reaction against a dilution series of known total RNA (of a similar type of sample).  Make sure to select a primer expressed similarly between the two preparations.  
- *Optional Downstream Step:*  RNA precipitation can be performed to concentrate, clean, or store the RNA.  For small quantities of RNA, a carrier is required.  Typical carriers used for this process are DNase-free glycogen or linear acrylamide.
  - RNA ppt:
    - 0.5 volumes of 3 M NaOAc, pH 5.2
    - 2.5 volumes 100 % EtOH
    - 2 µl (5 µg/µl) glycogen **OR** 2 µl (5 mg/ml) linear acrylamide.
    - Freeze overnight at -20 C, or 30 min at -80C
    - Spin 15,000 rpm, 4C, 25 min.
    - Wash with 300 – 500 ul 70 % EtOH.
    - Spin 2 min, remove supernatant thoroughly.
    - Dry on benchtop until the sample is just dried and the alcohol smell is gone (up to 10 min). \*\*\*Do not over dry!!!\*\*\*
    - Resuspend in RNase-free water.

### REAGENTS:
- Qiagen RNeasy Mini Columns, Qiagen, Cat#:74104, 74106
- Qiagen RNeasy Micro Kit (MinElute Columns), Qiagen, Cat #74004
- TRIzol, Invitrogen, Cat#:  15596-026
- Qiagen DNaseI On-Column Digestion, Qiagen, Cat#:79254
- Ambion Linear Acrylamide (5 mg/ml), Cat#: AM9520
- Ambion Glycogen (5 µg/µl), Cat#: AM9510

### REFERENCES:
- “Trizol/RNeasy RNA extraction protcol” by Mauricio Rodriguez-Lanetty
- Qiagen:  RNase-free DNase Set Handbook
- Qiagen:  RNeasy Mini Handbook, 4<sup>th</sup> ed.
- Ambion Top Ten: Tips for RNA Isolation: http://www.ambion.com/techlib/tn/115/14.html
- This protocol was modified and written up by Erin Osborne in the Lieb Lab at UNC
