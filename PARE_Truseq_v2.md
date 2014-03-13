# PARE-Truseq Library Preps v2.0

## Prepare >75 ug total RNA
Extract total RNA using TRIzol or other RNA extraction method. 
- Run RNA on GXII to check quality, RIN >7.
- Prepare RNA: use 75ug of total RNA as starting material. Adjust volume of 75ug total RNA to 100ul with DEPC-treated water. 

## mRNA Purification
Purify mRNA using Invitrogen Dynabeads mRNA direct kit: 

### Prepare beads:
- Transfer 200ul of Dynabeads in a 1.5ml tube on magnetic for 30sec and then pipette off the supernatant. 
- Remove tube from stand, and add 100ul Binding Buffer to calibrate beads, place on magnet and aspirate.
- Remove tube from stand, and add 100ul Binding Buffer to the Dynabeads (optimal hybridization conditions are a 1:1 ratio relative to sample volume).

### Denature RNA:
- Heat to 65oC for 2 min to disrupt secondary structures. Place on ice. 

### Isolate mRNA
- Add the total RNA to the Dynabeads/Binding Buffer suspension and mix thoroughly with pipette.
-  Rotate on a roller or mixer for 5 min at RT to allow the mRNA to anneal to the oligo (dT)25 on the beads using program F3 15 RPM. 
- Place the tube on the magnetic stand until the solution is clear and remove the supernatant. 
- Remove the tube from the stand and wash the mRNA- bead complex TWICE with 200ul Washing Buffer B. Remove all the supernatant between each washing step with the help of the magnetic stand. 
- Elute the mRNA from the beads by adding 16ul of Elution Buffer (10mM Tris-HCl, pH 7.5). 
- Place tube at 65oC for 2 min and then place immediately on the magnetic stand. Transfer 15ul of the eluted mRNA to a new tube. 
- Optional: recover another 1ul of purified mRNA and run on GXII

### Wash Dynabeads:
- Wash dynabeads in 100ul of bind buffer, then store in 100 ul bind buffer for re-use to purify the 5’ (ensure the beads are re-used for the same sample the second time).

## 5’ adapter ligation
															
|					|stock			|1x		|1x (ul)	|master (ul)|
|:------------------|:-------------:|:-----:|:---------:|-----------|
|polyA RNA			|				|		|   15	 	|	-- 		|
|5' RNA adapter 	|	200uM		| 10uM	|	1.25	| 			| 
|RNA ligase buffer	|10x			| 1x	| 2.5		|			|	 
|ATP				|	10mM		|	1uM	|	2.5	 	|			|
|Neb T4 RNA ligase I|	10,000 U/ml	|	15U	|	1.5	 	|			|
|RNase OUT			|40u/uL			| 20U	|	0.5	 	|			|
|dH2O	 	 		|				|		|	1.75	|			| 
| total				|				|		|	25	 	|	[11]	|

- Incubate @ 37oC for 2hr 
- Remove from 37oC and add 75ul of DEPC-treated water
- Heat kill at 65οC for 10min
- Place on ice 

### Prepare beads:
- Place Dynabeads from previous step on magnetic for 30sec and then pipette off the supernatant. 
- Remove tube from stand, and add 100ul Binding Buffer to re-calibrate beads, place on magnet and aspirate.
- Remove tube from stand, and add 100ul Binding Buffer.

### Purify ligated-mRNA:
- Add the 100ul ligation to the Dynabeads/Binding Buffer suspension and mix thoroughly with pipette.
-  Rotate on a roller or mixer for 5 min at RT to allow the mRNA to anneal to the oligo (dT)25 on the beads using program F3 15 RPM. 
- Place the tube on the magnetic stand until the solution is clear and remove the supernatant. 
- Remove the tube from the stand and wash the mRNA- bead complex TWICE with 200ul Washing Buffer B. Remove all the supernatant between each washing step with the help of the magnetic stand. 
- Elute the mRNA from the beads by adding 28.5ul of Elution Buffer (10mM Tris-HCl, pH 7.5). 
- Place tube at 65oC for 2 min and then place immediately on the magnetic stand. Transfer 27.5 of the eluted mRNA to a new tube.  

## Reverse transcription

### Denature RNA

	|5’-ligated RNA		|	27.5 ul		|
	|RT primer (100 um)	|	2 ul		|
	|:------------------|:-------------:|
	|Total			 	|	29.5 ul		| 
						

- 65oC for 5 mins, cool at RT

## 1st strand synthesis

	Final	1x (ul)	___x
RT RNA		29.5	--
5 x SSIII 
1st strand Buffer	1x	10	
dNTPs (10mM each)	400 uM	2	
0.1 M DTT	5 mM	2.5	--
RNase Out (40U/ul)	80U	2	
SSIII		4	
		50 ul	[10]

- 50oC for 3 hours
- 72 oC for 15 mins
- 4 oC hold

****Stopping point – store at -20 oC ****
 
PCRs
Run a long QC PCR and then a short PCR to amplify the template for MmeI.
QC PCR

	Final	1x (ul)	___x
1st strand cDNA		5	--
100% DMSO	3 %	1.5	
5x GC buffer	1x	10	
dNTPs (10mM each)	250 uM	1.25	
5’ short primer (10uM)	0.4 uM*	2.0	
3’ short primer 
(10 uM)	0.4 uM*	2.0	
dH2O		27.25	
Phusion	2 unit	1	
		50 ul	[45]

PCR cycling
	oC	min
1. 	98	1:00
2.	98	:30
3.	58	:30
4.	72	5:00
5.  Go to 2. 34 times
6. 	72	7:00
7. 	4	hold

Run 2 ul on GXII HS-DNA chip. Or on a 1.5% agarose gel.  
Should get a smear with distinct bands under 1 kb and above/around 3kb.
 
Short PCR

	Final	1x (ul)	___x
1st strand cDNA		20	--
100% DMSO	3 %	1.5	
5x GC buffer	1x	10	
dNTPs (10mM each)	250 uM	1.25	
5’ short primer (10uM)	0.4 uM*	2.0	
3’ short primer 
(10 uM)	0.4 uM*	2.0	
dH2O		12.25	
Phusion	2 unit	1	
		50 ul	[30]
PCR cycling
	oC	min
1. 	98	1:00
2.	98	:30
3.	58	:30
4.	72	5:00
5.  Go to 2. six times
6. 	72	7:00
7. 	4	hold

AMPure XP (1.8x) size selecton of cDNA reaction:

Add the following to a new non-stick, nuclease-free 0.2 ml PCR tube, strip or plate:
AMPure XP bead solution      90 μl
cDNA Reaction               	 50 μl

- Vigorously vortex tube and incubate at room temperature for 20 minutes.
- Place tube in magnetic stand for 5 minutes or until solution clears, to capture the beads. After the suspension is clear, remove and discard supernatant. Do not disturb bead pellet.
- With the tube on the magnetic stand, carefully add 180 μl of 80% EtOH to the bead pellet.
- Lift the tube off the magnetic stand, move it up one row and place it back onto the magnetic stand. Repeat 6 times. Allow the beads to settle. Discard the supernatant.
- With the tube on the magnetic stand, repeat the wash with 180 μl of 80% EtOH. Discard the supernatant. Do not disturb the beads. 
- Open the tube lid and transfer to a 37°C heat block for 3 minutes or until the beads are completely dry. Small cracks can be observed in the dried pellet.
- Add 16.8 μl of dH2O directly to the pellet and mix thoroughly using a pipette. 
- Incubate for 10 minutes.
- Place the tube in the magnetic stand for at least 2 minute to allow complete capture of the beads. When suspension is clear, transfer 15.8 ul of the library-containing supernatant to a new tube.

****Stopping point – store at -20 oC ****
 
Mme1 Digestion 

Purified PCR Product 	15.8ul
10X NEB4 Buffer		      2ul 
10X SAM (32mM) 		   0.2ul
Mme1 (2u/ul) 		      2ul  
total 				   20ul  

- 37οC (2hr)
- Remove from 37 οC, heat kill at 65 οC for 10min
- Let cool at RT (do NOT place on ice); 
- Prepare Duplex Adapter during heat kill step. 
Ligation of 3’-double-strand DNA Adapter
Make freshly prepared duplex adaptor by annealing 10% more oligo than needed, eg for 9 samples use 10ul of each:

dsDNA_2_Top 	1ul 
dsDNA_2_Bottom	1ul
TOTAL 		2ul

- 100oC(5min); 
- Slow cool down to RT by stepping temp down 5oC every 30sec (0.1oC /s to 25oC).  (~18min cycle)
- Keep at RT. 
Set up duplex ligation:
Mme1 digested PCR 					20ul 
Annealed Duplex Adaptor (100uM) 		2ul 
10X T4 DNA Ligase Buffer (w10mM ATP) 		3ul 
T4 DNA Ligase (400U/ul)** 				0.5ul 
dH2O 							4.5ul  
TOTAL 						30ul 

**Use the concentrated 2,000U/ul enzyme if doing quick ligation in quick ligation buffer…

Ligate at 16oC overnight 

****Stopping point – store at -20 oC ****
 
 
PAGE purify ds-DNA adapter ligation

The dsDNA adapter firstly can form dimers and then the ssDNA adapters once denatured can prime the final PCR if not removed and result in spurious adapter dimers dominating the final library.  This happened when using the dsDNA adapter that had the phos- group on he wrong end, so it probably has to be removed, but have to check. Will do this on this prep.

Samples are not yet indexed therefore preferably leave spaces between samples, and run sample groups of different gels (ie only replicates on the same gel).

12 % native PAGE (0.5x TBE)
- 1.5ml spacers (or 1.0mm and will have leftovers), 2 gels

	2x 1.5mm gels
(4x 1.0 mm gels)	4 x 1.5 mm gels
40% acrylamide
(acryl: bis 1:19)	9.0 ml	15.0 ml
10 x TBE	1.5 ml	2.5 ml
dH2O	up to 30ml	up to 50ml
Optional 0.22uM filter, add then quickly pour:		
10% APS
(100mg/ml H20)	210ul	350ul
TEMED	21	35ul


- Add 5x Biorad loading dye (GLB) to samples, max volume is ~ ul(?) for 1.5mm gel

Run Gel:
- 180 V
- ~50 mins until bromo blue just above bottom of gel
- Add 73 bp marker (5 ul) (ELIP2 is PCR product) Not needed really
- Add 0.25ug Invitrogen 10bp ladder (0.25ul into 5 ul H2O + 2ul GLB) 
Stain Gel:
- Stain 5 mins in 100ml H2O + 10ul EtBr (final – 1mg/ml), rinse twice in MQ H2O
Cut bands:
- Align sterile razor with the 60 and 70 bp markers and cut to capture the band corresponding to the ligation product (63bp); avoid adapter dimers (44bp) and place slices in shredder tubes.


Gel Purification of ligation:
Assemble gel shredder tubes: 
- Make 3 small holes in the bottom of a 0.5ml tube with a fine gauge syringe (eg 25 G - 0.5mm), large gauges with make it hard to pipette gel debris later.
- Place shredder in 2ml low bind tube (2ml for better mixing of debris)
Shred:
- Add gel slice and spin at max rcf for 2 mins, 
o	After spin small debris that get stuck in shredder can be tapped out into collection tube.
- Add 450 ul DEPC H2O
- Elute DNA overnight at 4oC by rotating on the inteli mixer F5 60 RPM
- Pre-chill 100% ethanol at -20oC for next day
Precipitate and recover DNA:
- Put 100% ethanol in the -80oC to 10 mins if you forgot yesterday…
- The following day, add gel debris slurry to Spin-X 0.45 uM spin filter, and spin 2 mins max speed 4oC
- Keep flow-through and add:
o	2 ul Glycoblue
o	46 ul NaOAc (4M)
o	1400 ul  EtOH (pre-chilled)
- Invert 11 times
- Spin 20,000 RCF x 20 mins at 4oC, then aspirate supernatant 
- Wash with 500ul of 70% ethanol at RT, spin 2 mins 7,000 RCF and aspirate ethanol
o	Pulse spin again and aspirate with fine tip if necessary to remove trace ethanol 
- Dry for 5-10 mins at 37oC
- Re-suspend in 31ul of 10mM Tris pH 8.5

 
Pilot PCR – ½ reactions

Use 14 ul of the ligation to test the number of PCR cycles neede d using a couple of samples eg one of each replicate group (not all in case further optimization is needed).  Start with 10- 15 cycles, which should be sufficient (less for RNA decay mutants), use the PAGE purification of the ligation as a guide. 

Note: Ideally, all samples should be amplified on the same machine at the same time with the same cycle number once optimization is complete. 


	Final	1x (ul)	___x
DNA		14	--
100% DMSO	3 %	0.75	
5x GC buffer	1x	5	
dNTPs (10mM each)	250 uM	0.625	
3’ TruSeq index primer (10uM)**	0.4 uM*	1.0	--
5’ PARE Final PCR primer (10 uM)	0.4 uM*	1.0	
dH2O		2.375	
Phusion	1 unit	0.25	
		25 ul	[10]

*Note that this is 4x conc in the Truseq-PARE protocol I was sent from Blake’s lab (0.1um); but it seemed low so I increased it.  German et al Nat Biotec used 0.5 uM in the original published protocol.
**The Illumina support site reports that any index combination shows minimal variability, including low-plex pools.
PCR cycling
	oC	min
1. 	98	:30
2.	98	:10
3.	58	:30
4.	72	:20
5. Go to 2. more than a couple of times (nine?)
6. 	72	10:00
7. 	4	hold

Run 2 ul on GXII HS-DNA chip. 

Final PCR
Repeat PCR conditions as per pilot with optimized cycle number. 

PAGE purify and concentrate final library

Samples are not indexed now therefore spaces between samples are not so important and samples groups can be mixed on the same gel.  Probably need to run each sample over 2 lanes (~30ul total).
6 % native PAGE (0.5x TBE)

	2x 1.5mm gels
(4x 1.0 mm gels)	4 x 1.5 mm gels
40% acrylamide
(acryl: bis 1:19)	4.5 ml	7.5 ml
10 x TBE	1.5 ml	2.5 ml
dH2O	up to 30ml	up to 50ml
Optional 0.22uM filter, add then quickly pour:		
10% APS
(100mg/ml H20)	210ul	350ul
TEMED	21	35ul


- Add 5x Biorad loading dye (GLB) to samples, max volume is ~25 ul(?) for 1.0mm gel, max volume is ~ ul(?) for 1.5mm gel

Run Gel:
- 145 V
- ~60 mins until xylene cyanol is 1 cm above bottom of gel
- Add 123 bp marker (ACT7 PCR product) Not needed really
- Add 0.25ug Invitrogen 10bp ladder (0.25ul into 5 ul H2O + 2ul GLB) 
Stain Gel:
- Stain 5 mins in 100ml H2O + 10ul EtBr (final – 1mg/ml), rinse twice in MQ H2O
Cut bands:
- Align sterile razor just above the 120pb marker and the just below the 140bp marker and cut to capture the band corresponding to the final PCR product (128bp);) and place slices in shredder tubes.

Gel Purification of PCR:
Gel purify, as above for the ligation clean up step. 
Reagents
Oligos

5′-PARE RNA adaptor 5′-GUUCAGAGUUCUACAGUCCGAC-3′ 

Target RT-primer: 
5' CGA GCA CAG AAT TAA TAC GAC TTT TTT TTT TTT TTT TTT

Short PCR primer:
5′-adapter primer 5′-GTTCAGAGTTCTACAGTCCGAC-3′
3′-adapter primer 5′-CGAGCACAGAATTAATACGACT-3′

dsDNA adapter (PARE TruSeq Duplex) (PAGE purified): 
*dsDNA_2_Top: 5' Phos-TGG AAT TCT CGG GTG CCA AGG
dsDNA_2_Bottom:  5'-CCT TGG CAC CCG AGA ATT CCA NN

final PCR primer (P2 sRNA long primer aka “old PARE primer)
5': AATGATACGGCGACCACCGACAGGTTCAGAGTTCTACAGTC

Truseq small RNA kit primers (eg from #RS-200-0012):
Truseq 3' sRNA primer
Indexes 1~24

PARE TruSeqV2 read primer:
5’ – CCACCGACAGGTTCAGAGTTCTACAGTCCGAC – 3’
“I would recommend PAGE purification, it's a small price to pay when considering the cost of Illumina sequencing in both time and $$. I resuspend to 100uM in TE, aliquot, then dilute to 500nM (1:200) for use. This is the standard procedure that Illumina uses for their sequencing primers.” [Brewster Kingham brucek@udel.edu]


*note that Jixan Zhai’s published TruSeq protocol does not have the 5’ phosphate, perhaps this helps to minimize duplex self-ligation.  That said; I only need ~8 cycles for the final PCR, where as Jixan reports 15 cycle final PCR… 
Reagents

VENDOR	Product	CAT#	Unit	UNIT AUD$
Life Technologies (invitrogen)	Dynabeads® mRNA Purification Kit for mRNA Purification from Total RNA Preps	610-06	2mL	709
Life Technologies (invitrogen)	RNaseOUT™ Recombinant Ribonuclease Inhibitor	10777-019	5000U	163.68
Life Technologies (invitrogen)	TRIzol® Reagent	15596018	200ml	592
Life Technologies (invitrogen)	SuperScript III Reverse Transcriptase	18080085	4x10000	1577.8
Sigma	Costar® Spin-X® centrifuge tube filters	CLS8162-96EA	96 tubes	127
NEB/Genesearch	APT (10mM)	P0756S	1ml	47
NEB/Genesearch	Neb T4 RNA ligase I (ssRNA ligase) 10,000 U/ml	M0204S	1000U	92
NEB/Genesearch	MmeI (2,000U/ml)	R0637L	500U	399
NEB/Genesearch	T4 DNA ligase (400U/ul)	M0202S	20,000U	101
Life Technologies (invitrogen)	10bp DNA ladder	10821-015	50ug (50ul)	193
NEB/Genesearch	Phusion High-Fidelity DNA Polymerase
(100 units)	M0530S	100 U	149.40


