CRISPR sgRNA protocol (adapted from Gagnon et al., 2014)

**Target site selection**

To knock out the function of a protein-coding gene, the stop codon cassette should be introduced downstream of the start codon. Transcripts resulting from a modified gene will often be degraded by nonsense-mediated decay, assuming there is a downstream exon-exon junction. Targets can be identified manually or using an online webtool such as CHOPCHOP (recommended, see below). For manual targeting, the user can search the sequence of the gene for (G/A)(G/A)-N<sub>19</sub>-GG, and identify targets with >50% G/C content downstream of the empirically- or algorithmically-determined start codon.

To aid in target site selection, we developed an online webtool named CHOPCHOP (<https://chopchop.rc.fas.harvard.edu/>), which allows easy visualization of candidate Cas9 target sites within the gene, and predicts specificity using an algorithm that searches the genome for off-target sites.

As an example, here is the result of a query in CHOPCHOP for the *ctgfa* gene in zebrafish. We will follow this gene through the mutagenesis pipeline in this protocol. 

First, access the website listed above and type ‘ctgfa’ into the search box. Next, click ‘Toggle advanced options,’ select CRISPR, and click the radio button requiring a 5’ GG.  Now click “Find Target Sites,” which produces a window of results. The screen shot below indicates the position of the target sites on the *ctgfa* gene.



The highest scored target site for this sgRNA is GGGGCGGCACTTCAGGGCAGTGG. It was selected because of high G/C content, a guanine base adjacent to the protospacer adjacent motif (PAM), and because it is at the 5’ end of the open reading frame.

The first twenty bases (GGGGCGGCACTTCAGGGCAG) are the spacer region, and will be included in the sgRNA. The PAM is the last three bases (TGG). The PAM is not included in the sgRNA sequence, but is required in the genome for Cas9 targeting. 

**Generate sgRNA**



Above is a diagram (also Supplemental Figure S1) that describes our protocol for cloning-independent generation of sgRNAs. For each sgRNA, the user must order a 60 base oligonucleotide (“gene-specific oligo”) containing 1) a promoter for in vitro transcription (blue), 2) the 20 base spacer region specific to the target site (black), and 3) an overlap region that anneals to the constant oligonucleotide (grey).  The user must order one gene-specific oligo per target and the 80 base constant oligonucleotide (the same for all sgRNA templates).

The user can select the T7 or SP6 (**recommended\_and used in the Lo lab**) promoter.

T7: TAATACGACTCACTATA

SP6: ATTTAGGTGACACTATA

Overlap region: GTTTTAGAGCTAGAAATAGCAAG

The gene-specific oligo using SP6 will have the architecture shown below, with the Ns replaced with the 20 bases specific to the target:

ATTTAGGTGACACTATA-<b>N<sub>20</sub>-</b>GTTTTAGAGCTAGAAATAGCAAG

The gene-specific oligo for the example gene *ctgfa* has this sequence:

ATTTAGGTGACACTATAGGGGCGGCACTTCAGGGCAGGTTTTAGAGCTAGAAATAGCAAG

The constant oligonucleotide, regardless of promoter or target gene choice has this sequence:

AAAAGCACCGACTCGGTGCCACTTTTTCAAGTTGATAACGGACTAGCCTTATTTTAACTTGCTATTTCTAGCTCTAAAAC

We order standard desalted oligos from Life Technologies or IDT, with no additional purification.  


\*


CRISPR sgRNA protocol (adapted from Gagnon et al., 2014), from Te-Wen Lo


*Anneal oligos:*

Gene-specific oligo (100 µM)		4 µl

Constant oligonucleotide (100 µM)	4 µl

10X PCR Buffer				10 mL

2\.5 mM dNTPs				8 mL

DNA polymerase				2 mL

dH<sub>2</sub>0            					72 mL

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Total					          100 µl

Run OLIGOFIL program on PCR machine:

1\. 95˚C			2 minutes

2\. 95˚C                               30 seconds

3\. 50°C			2 minutes

4\. 72°C			5 minutes

5\. repeat steps 2-4 three times (so a total of 4 cycles)

6\. 4˚C			hold

Purify the template using a PCR cleanup column, and elute in 30 µl of water (expected: 100-200 ng/µl DNA)

Run 2 µl on an agarose gel to verify a product of the correct size (dominant band should be ~120 bp).

Determine concentration using the nanodrop.


*Transcribe sgRNA* (we use Ambion MEGAscript T7/SP6 Kit):

Thaw all reagents on ice.

Assemble in PCR tubes at room temperature.  

ATP				6 µl

GTP				6 µl

CTP				6 µl

UTP				6 µl

10x buffer			6 µl

T7/SP6 enzyme mix		6 µl

Template			X µl (0.45 µg)

Water				(up to 60 ml total)

Total:				60 µl

Incubate overnight at 37˚C in PCR machine.

Add 3 µl TURBO DNase (included in Ambion transcription kit),

Incubate for 15 minutes at 37˚C.*

*Cleanup sgRNA transcription reaction*

-Add 10 µl 5 M ammonium acetate (included in transcription kit) and 60 µl 100% ethanol.

-Mix well, incubate for 20 minutes at -80˚C until frozen (can be left up to overnight).  

-Centrifuge for 15 minutes at 4˚C, maximum speed.

-Remove the supernatant and add 1 ml 70% ethanol.

-Centrifuge for 5 minutes at 4˚C, maximum speed.

-Remove supernatant, quick spin down the ethanol on the sides of the tube, remove liquid with a 200 µl pipette tip.

-Dry at room temperature for a few minutes and resuspend in 20 µl water.

-Determine RNA concentration using the Nanodrop.  Want over 2000 ng/ul

-Run on a gel- should see a band at ~100bp

4

