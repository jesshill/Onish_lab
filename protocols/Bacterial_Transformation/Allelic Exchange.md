**Allelic exchange protocol for gene knockout, point mutagenesis, tagging**

***In silico construct building***

Digest pCVD443 at XbaI and SacI sites and ligate the ***locus*** containing your ***allele of interest*** into the digested pCVD443 in silico. The ***allele of interest*** could be a point mutation allele, or a large-deletion allele, or a two-gene operon/fusion of the gene being studied with a tag protein. The ***locus*** containing your allele of interest is a region with your allele of interest in the middle flanked by 2 regions of 1-1.5 kb upstream and downstream of it (homology arms for recombination). Double check to make sure the allele of interest does not cause frame shift of its downstream genes (in the 3’ flanking region). Based on this in silico construct, appropriate primers can be picked to clone fragments that will be then ligated together with restriction-digested pCVD443 by Gibson assembly.

**Note:** pCVD443 is a low copy-number plasmid, and therefore you might have to grow a large volume of overnight culture to harvest/miniprep enough amount of plasmids for digestion followed by subsequent column purification (no less than 5mL, I usually spin down cells from 10 mL culture to miniprep).

**Make ahead:** electrocompetent *E. coli* SM10, Kan+Strep LB plates, 10% sucrose LB plates.

***Phusion PCR and Gibson Assembly***

- Do PCR with the primers picked from the in silico construct. 
- Triple digest miniprepped pCVD443 with XbaI, SacI and SphI (the addition of SphI is to maximize the digestion efficiency and therefore the yield of linearized plasmids).
- Column-purify all the PCR fragments and the digested pCVD443. 
- Perform Gibson assembly for PCR fragments and pCVD443 with NEB HiFi DNA Assembly kit according to manufacturer’s recommendation in terms of molarities of fragments, ratios, and incubation duration.
- Transform *E. coli* SM10 with the Gibson mixture by electroporation using BioRad Micropulser Ec2 program (V=2.5kV) and 0.2 cm cuvette. After outgrowth of the electroporated population in SOB for at least 1 hour, plate on Amp LB plate to select for transformants (pCVD443 has both AmpR and KanR; however, SM10 is inherently KanR so in order to maintain the plasmid, select with Amp).

***Mating and selection for recombination***

- Mate a transformant *E. coli* SM10 (hosting pCVD443 harboring the locus with your allele of interest) with your bacterial species of interest.
- Select for the first recombination event with Kan+Strep LB plates.
- Pick a few colonies on Kan+Strep LB plates, grow in 5 mL cultures overnight with antibiotics. These cultures can be used for 2 things: a) I usually take 700 uL of each culture and make a temporary glycerol stock of each of these clones as stocks for starting material of second selection; and b) Take 1 mL of the culture, spin the cells down, wash twice with LB to get rid of antibiotics and resuspend in 1 mL of LB, then plate about 200 uL of this suspension on 10% sucrose LB plates (no antibiotics) for selection of second recombination event.
- Screen the 10% sucrose LB plates for your allele-exchanged/knockout/tagged clones. If you have a marker in your construct (in case of tagging with fluorescent protein), this will be easy. Otherwise, you’ll have to screen by colony PCR with primers that flank your allele. The second recombination event either swaps everything out and gives you back WT or happens at the second homology arm and gives you the allelic exchanged clones. 

**Subportocol for electrocompetent cells**:

- Autoclave 2x 500 mL of LB in 1L flask (for bacterial growth) and also sterilize about 600 mL of 10% glycerol (for washing cells).
- Streak out *E. coli* SM10 on Kan LB plates.
- Pick a colony to grow several seeding cultures (5 mL each) overnight.
- Seed 5 mL of the overnight culture into 500 mL of LB and grow at 37°C, 225 rpm. Depending on how fast you want to grow them, the seeding volume may increase. Check OD<sub>600</sub> after a few hours until the OD<sub>600</sub> reaches 0.5-0.6 (you can let it go to 0.7-0.8, which means more cells, but I prefer them to be in mid log phase). Chill cells on ice (4°C) for 30 min. 
- Pre-chill centrifuge bottles/containers, 50 mL Falcon tubes, 10% glycerol, and microcentrifuge tubes that you will aliquot the electrocompetent cells into.

Note: Everything from this step onwards should be kept on ice.

- Transfer 1 L of cultures into pre-chilled centrifuge bottles, spin at 4200 g at 4°C for 15 min. Pour off the supernatant, be careful not to pour off the pellet in the process since these are loose pellets.
- Resuspend the cell pellets with 50 mL of chilled 10% glycerol either by vortexing or pipetting with serological pipette. Transfer to 50 mL Falcon tubes.
- Centrifuge at 4200 g, 4°C for 15 min. Pour off supernatant, and resuspend in another 50 mL of 10% glycerol. This is wash #1.
- Repeat the washing step for 4 more times for a total of 5 washes. The washes are to remove as much as possible salts in LB to prevent arcing during electroporation.
- Pour off the supernatant and resuspend cells gently in the residual 10% glycerol (the liquid that falls back after being poured off, and hence, it’s a very thick suspension). Aliquot 50 uL into microcentrifuge tubes and store at -80°C.

**Subprotocol for electroporation:**

- Coordinate with Shikuma lab to get permission to use their electroporator.
- Once you have everything ready (DNA mix, pipettes and tips, prechilled cuvettes) for the actual electroporation step, take the number of aliquots of electrocompetent cells you need (1 aliquot per condition) and let them thaw on ice (about 2-3 min, don’t let it thaw on ice like 30 min or 1 hr before electroporation since the efficiency will reduce dramatically).
- Turn on the electroporator, choose Ec2 program.

**Note:** the next few steps should be done as quick as possible. If you have multiple samples, do one at a time, and keep the rest on ice. Competent cells are fragile beings, they will shatter (and so will your transformation) very easily!!! 

- Mix 2-5 uL into a tube of electrocompetent cells. Pipette the whole competent cell + DNA mixture into a prechilled 2 mm cuvette, tap onto the bench one to pull the mixture to the bottom of the cuvette.

**Note:** The amount of DNA mixture used can be more than 5 uL if needed, but you will have to empirically determine this for yourself. The point is sometimes you’ll need more DNA for sufficient transformation, and this depends on the competent cells, but you don’t want too much since there’s salt in your DNA ligation mixture, which will make the whole mixture explode when electric current runs through the cuvette – a.k.a arcing – you’ll hear a relatively loud (micro explosion) sound and your mixture will splash all over the places. 

- Before inserting the cuvette to the machine, pipette 1 mL of sterilized, room temp LB (or SOB) at the ready. Insert the cuvette onto the slider in appropriate position and push the slider until you hear a small clicking sound – like the cuvette locked onto the platform). Press the button with an electric symbol , you’ll hear fast beeping sound, and then a continuous sound, at which point you pull out the cuvette and immediately pipette the 1 mL LB into the cuvette, and pipette the whole mixture (LB + electroporated cells) out into a sterile 1.5 mL tube and incubate at 37C shaking incubator for at least 1 hour (the 1 hr is usually recommended in many protocols, but I usually do 2 hr, any shorter than 1 hr would sharply reduce the survival of electroporated cells). 

**Note:** This step should be performed as quickly as possible, especially when you start to hear the continuous sound of the machine, you should pull out the cuvette and pipette the LB into it. Delayed resuspension of electroporated cells into LB will also reduce transforming efficiency a lot. After pipetting the cell suspension into 1.5 mL tube, ideally, we put it in the incubator right away, but you’ll probably have to move stuff back to our lab and use our incubator, so during the transitioning period, keep the cell suspension at RT, don’t put on ice because it will create heat shock when you put it in the 37C incubator, which will kill the fragile cells at this stage.

- After the recovery time in the incubator, spread 150 uL onto 1 Carb/Amp LB plate, spin down the remaining 850 uL, discard the liquid but leave about 100-200 uL, resuspend the pellet and spread all of it onto another Carb/Amp LB plate (to plate everything from the electroporated population and therefore help increase the chance of getting the transformant).

**Subprotocol for mating:**

- Grow the parental strains in (overnight) cultures with appropriate antibiotics to prevent contamination as well as maintaining the plasmid in one of the parental strains. The OD<sub>600</sub> at which I usually perform mating is 0.5-0.7.
- Pellet the bacteria and wash with LB for several times to remove antibiotics as much as possible (to avoid cross-killing the other parental strain). Resuspend the washed pellets and mix recipient : donor in either 1:1 or 1:10 ratio. Mix thoroughly and pellet the mixture, discard most of the liquid, leave only about 100 uL or even the residual liquid would also be sufficient. Resuspend again (quite thick mixture) and spot plate on LB agar plate without antibiotics (~ 30 uL spots). Incubate at recipient growth temperature.
- After 1-2 days of incubation, scrape a little bit of the spot, resuspend in LB and plate on Strep+Kan LB agar plates. 

