#MethylC-seq library preps for Illumina Sequencing v2.6

*protocol from Lister Lab Dec, 2013*

##Fragment gDNA

1. Start with 1-2 ug gDNA (use 1ug of fragmented DNA in library prep)
2. Prepare unmethylated phage DNA stock at 10 ng/ul and/or 2.5ng/ul, spike in 5ng (0.5% w/w).
  * eg stock at 491ng/ul: add 2.04ul to 97.96 ul EB to give 10ng/ul stock.
  * add 25ul of 10ng/ul stock to 75ul EB to make 2.5ng/ul stock
  * check stock dilutions on Qubit
3. Dilute 1000ng of gDNA sample in 128ul of EB and add 2.0ul of the 2.5ng/ul phage DNA (5ng; 0.5% w/w)
4. Sonicate 125ul on Convaris 200bp protocol, eg:
  * 1 x 60sec cycle of Duty 10%, intensity 5, cycles/burst 200
5. Run 10ul on a 1% gel (~120v x 30 mins) to check for smear from ~100-500bp
 

##Clean up fragmented DNA

1. MinElute PCR clean as per manual
2. ELute twice with 18ul EB for a total 36 ul elution
3. Transfer 34ul for End Repair

## End Repair End it Kit

| 		| 1x (ul)	| __x	|
|:--		|:-:		|:-:	|
|DNA sample 	|34 		|--	|
|10x Buffer	|5		|	|
|10mM dNTP mix	|5		|	|
|10mM ATP	|5		|	|
|End It Enzyme Mix|1		|	|
|total		|50ul		|[16ul]	|

Mix tubes gently, spin down briefly and incubate at RT for 45 mins

##Clean-up Repaired DNA

1. MinElute PCR clean as per manual
2. ELute twice with 17ul EB for a total 34 ul elution
3. Transfer 32ul for A-tailing

##A-tail: add 'A' over-hang to 3' ends

| 		| 1x (ul)	| __x	|
|:--		|:-:		|:-:	|
|DNA sample 	|32 		|--	|
|10x Buffer	|5		|	|
|1mM dATP	|10		|	|
|Klenow exo (low conc) 	|3		|	|
|total		|50ul		|[18ul]	|

Mix tubes gently, spin down briefly and incubate on a PCR machine for 30 mins at 30°C

### AMPure XP (1.55x) clean A-tail reaction:
Add the following to a new non-stick, nuclease-free 0.2 ml PCR tube, strip or plate:

|Reagent			|volume	|
|:------------------------------|:------:|
|AMPure XP bead solution	|78 μl	|
|cDNA Reaction          	|50 μl	|

- Vigorously vortex tube and incubate at room temperature for 20 minutes.
- Place tube in magnetic stand for 5 minutes or until solution clears, to capture the beads. After the suspension is clear, remove and discard supernatant. Do not disturb bead pellet.
- With the tube on the magnetic stand, carefully add 180 μl of 80% EtOH to the bead pellet.
- Lift the tube off the magnetic stand, move it up one row and place it back onto the magnetic stand. Repeat 6 times. Allow the beads to settle. Discard the supernatant.
- With the tube on the magnetic stand, repeat the wash with 180 μl of 80% EtOH. Discard the supernatant. Do not disturb the beads. 
- Open the tube lid and transfer to a 37°C heat block for 3 minutes or until the beads are completely dry. Small cracks can be observed in the dried pellet.
- Add 43 μl of dH<sub>2</sub>O directly to the pellet and mix thoroughly using a pipette. 
- Incubate for 10 minutes.
- Place the tube in the magnetic stand for at least 2 minute to allow complete capture of the beads. When suspension is clear, transfer 41.5 ul of the library-containing supernatant to a new tube.


##Ligate methylated adapters - Bioo Scientific NEXTflex

| 			| 1x (ul)	| __x	|
|:--			|:-:		|:-:	|
|DNA sample 		|41.5		|--	|
|10x Buffer (with ATP)	|5		|	|
|Adapter		|2.25		|--	|
|T4 DNA ligase (low conc)|1.25		|	|
|total			|50ul		|[6.25ul]|

Mix tubes gently, spin down briefly and incubate on a PCR machine overnight at 16°C

*Note: could do quick ligation with conc enzyme*


*Note2: original ligation volume was 25ul using 5ul of TruSeq V2 indicies from RNAseq kit*


### AMPure XP (1.3x) clean ligation reaction:
Add the following to a new non-stick, nuclease-free 0.2 ml PCR tube, strip or plate:

|Reagent			|volume	|
|:------------------------------|:------:|
|AMPure XP bead solution	|65 μl	|
|cDNA Reaction          	|50 μl	|

- Vigorously vortex tube and incubate at room temperature for 20 minutes.
- Place tube in magnetic stand for 5 minutes or until solution clears, to capture the beads. After the suspension is clear, remove and discard supernatant. Do not disturb bead pellet.
- With the tube on the magnetic stand, carefully add 180 μl of 80% EtOH to the bead pellet.
- Lift the tube off the magnetic stand, move it up one row and place it back onto the magnetic stand. Repeat 6 times. Allow the beads to settle. Discard the supernatant.
- With the tube on the magnetic stand, repeat the wash with 180 μl of 80% EtOH. Discard the supernatant. Do not disturb the beads. 
- Open the tube lid and transfer to a 37°C heat block for 3 minutes or until the beads are completely dry. Small cracks can be observed in the dried pellet.
- Add 22 μl of dH<sub>2</sub>O directly to the pellet and mix thoroughly using a pipette. 
- Incubate for 10 minutes.
- Place the tube in the magnetic stand for at least 2 minute to allow complete capture of the beads. When suspension is clear, transfer 21 ul of the library-containing supernatant to a new tube.

## Qubit
Qubit 1 ul of the clean ligation to check concentration, use 450ng or less for the BS-conversion.


## Bisulfite conversion
1. Dilute samples to 450ng or less in 20 ul of EB.  
  * If more than 450ng is used, non-conversion rate increases
2. Perform conversion as per MethylCode kit instructions
  * At step 2 - conversion - split the samples into 2 new tubes after mixing (75ul each), to fit in PCR machine (max vol usually 100ul) and ansure no DNA sticks up top and avoids conversion
3. ELute in 42 ul (unless input DNA is very low).  
  * 40ul enables duplicate PCR reactions

  
## Amplification and adapter extension of PCR
Multiple PCR reactions (e.g. 2) can improve data quality i.e. less clonal reads.  However, if input DNA is very low it's better to only do one PCR.

Start with 1 PCR using 4-6 cycles, check the raw PCR on the GXII then, if all looks good run the duplicate PCR and then proceed to AMPure purification.

|			|1x (ul)	| __x|
|:----------------------|:------:	|:--:|
|BS converted DNA 	|20 		|--	|
|Kapa U+ 2x PCR mix   	|25 		|	|
|NEXTflex Primer mix	|2		|	|
|dH<sub>2</sub>O      	|3		|	|
|TOTAL 			|50 		|[30]	|

PCR cycling

|step	|	1	|	2	|	3	|	4	|	5	|	6	|7	|
|:------|:--------------|:--------------|:--------------|:--------------|:--------------|:--------------|:------|
|temp	|95		|98		|65		|72		|*Go to 2 x 3-5 times|	72	|4 	|
|min	|2:00		|0:20		|0:15		|1:00		|		|	10:00	|hold	|

### AMPure XP (1.3x) clean PCR reactions:
Add the following to a new non-stick, nuclease-free 0.2 ml PCR tube, strip or plate:

*Adjust volumes accordingly if some of the PCR was used for QC*

|Reagent			|volume	|
|:------------------------------|:------:|
|AMPure XP bead solution	|65 μl	|
|cDNA Reaction          	|50 μl	|

- Vigorously vortex tube and incubate at room temperature for 20 minutes.
- Place tube in magnetic stand for 5 minutes or until solution clears, to capture the beads. After the suspension is clear, remove and discard supernatant. Do not disturb bead pellet.
- With the tube on the magnetic stand, carefully add 180 μl of 80% EtOH to the bead pellet.
- Lift the tube off the magnetic stand, move it up one row and place it back onto the magnetic stand. Repeat 6 times. Allow the beads to settle. Discard the supernatant.
- With the tube on the magnetic stand, repeat the wash with 180 μl of 80% EtOH. Discard the supernatant. Do not disturb the beads. 
- Open the tube lid and transfer to a 37°C heat block for 3 minutes or until the beads are completely dry. Small cracks can be observed in the dried pellet.
- Add 21 μl of dH<sub>2</sub>O directly to the pellet and mix thoroughly using a pipette. 
- Incubate for 10 minutes.
- Place the tube in the magnetic stand for at least 2 minute to allow complete capture of the beads. When suspension is clear, transfer 20 ul of the library-containing supernatant to a new tube.

## qPCR to determine molarity of libraries

Use Kapa qPCR kit according to manufacturer instructions.  Should only need to make 1:1000 and 1:2000 dilution to be within the range of standards 1, 2 and 3.

## Reagents

| Reagent	| Supplier 	| Cat#	| size		| price ($$)	| Distributor 	| # 5mC preps 	|
|:--		|:--		|:--:	|:--:		|:--:		|:--		|:-:		|
|Phage DNA	| Promega	|D1521	|250μg		|$109		|Promega 	| inf 		|
|MinElute PCR clean Up	|Qiagen	|28004	|50 preps	|$241 		|Qiagen		| 25		|	
|End-It Kit	|Epicentre 	|ER81050|50 preps	| $239		| Gene Target Solutions Pty Ltd	| 50|
|dATP		|Life Tech (Invitrogen)	|18252-015 |250ul (10mM) |$122	|Life Tech	|		|
|MethylCode Kit	|Life Tech (Invitrogen)	|MECOV-50 |50	|$386		| Life Tech	|	50 (10x single use lots)	|	
|Next Flex Bisulfite-Seq Barcode kit	|Bioo Scientific	|511911	|48 rxns (6 barcodes)	|$682 |	Geneworks |24 (48 x 50ul rxns)|
|Kapa HiFi HotStart U+ 2x readymix	|Kapa Biosystems	|KK2801	|1.25ml |$469|Geneworks |25 (50 x 50ul rxns) |
|Klenow exo (low conc)	|NEB	|M0212L	|1,000 units @5,000 units/ml |$236	|Gensearch	|66		|	
|T4 DNA Ligase (low conc)|NEB 	|M0202L	|100,000 units @400,000 units/ml|$256|Gensearch	|200		|		
|Library Quantification Kit - Illumina/LightCycler® 480	|Kapa Biosystems |KK4854 | |$866.31 | Geneworks|		|
|Covaris Tubes 6x16mm slit cap micro tube|Kbiosciences|520045	|25		|$226		|TrendBio		|25		|
					
Optional:					
Qubit HS dsDNA kit	Life Tech (Invitrogen)				
Sera Pure (Sera-Mag SpeedBeads)	Thermo Scientific	65152105050250	15 ml (dilute 1ml :50ml)		


