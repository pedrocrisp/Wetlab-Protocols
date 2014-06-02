#Illumina Truseq mRNA stranded kit protocol, one-third reaction volumes

  *Largely reproduced from [Ethan Ford](http://ethanomics.wordpress.com/truseq-rna-library-preparation-kit-v2-using-one-third-the-reagents/) with modifications* 


**PolyA select mRNA**

1. Dilute up to 1.3 μg total RNA in H<sub>2</sub>O to a final volume of 16.7 μl.
2. Vortex RNA Purification Beads and add 16.7 μl to RNA sample.
3. Mix by pipeting up and down until beads are in a homogenous suspension.
4. Incubate in thermocycler:

   |˚C | time|
   |:-:|:-:|
   |65˚C | 5 min|
   |4˚C | hold |

5. When thermocycler reaches 4˚C remove sample and place on bench at room temperature for 5 min.
6. Place sample in magnetic rack for 5 min.
7. Remove and discard all the supernatant.
8. Remove sample from rack.
9. Add 66.7 μl of Bead Washing Buffer and pipet up and down until beads are in a homogenous suspension.
10. Place the sample back in the magnetic rack for 5 min.
11. Remove and discard all the supernatant.
12. Add 16.7 μl of Elution Buffer and pipet up and down until beads are in a homogenous suspension.
13. Incubate in thermocycler:

   |˚C | time|
   |:-:|:-:|
   |80˚C | 2 min|
   |25˚C | hold |

14. Remove sample from thermocycler when it reaches 25˚ C and keep at room temp.
15. Add 16.7 μl of Bead Binding Buffer and pipet up and down until beads are in a homogenous suspension.
16. Incubate at room temperature for 5 min.
17. Place sample in magnetic separator for 5 min.
18. Remove and discard all supernatant.
19. Remove sample from rack.
20. Add 66.7 μl of Bead Washing Buffer and pipet up and down until beads are in a homogenous suspension.
21. Place sample in magnetic separator for 5 min.
22. Remove and discard all supernatant.
23. Add 6.5 μl Elute, Prime, Fragment Mix and pipet up and down until beads are in a homogenous suspension.
24. Incubate in thermocycler (frag time can be between 1-8 mins, although median fragment size does not change significantly, only tail increases):

   |˚C | time|
   |:-:|:-:|
   |94˚C | 7 min|
   |4˚C | hold |

25. Immediately place sample in magnetic rack for 5 min.
26. Transfer 5.7 μl of the supernatant to a new 0.2 ml PCR tube.

   **First Strand Synthesis**

27. Make First Strand Mater Mix, add 2.7 ul to RNA and mix gently:


   | Component 			| 1x 		| __x Master 	|
   |:-:|:-:|:-:|
   | RNA 			| 5.7 ul	| --- 		|
   | Illumina 1st Strand Buffer	| 2.43 ul	|  		|
   | SSIII (or SSII) 		| 0.27 ul	| 		|
   | Total			| 8.4 ul	| [2.7]		|

   *User provides SuperScript which is mixed 1:9 with the Illumina buffer*

29. Incubate in thermocycler:

   |˚C | time|
   |:-:|:-:|
   |25˚C | 10 min|
   |50˚C* | 15 mins |
   |70˚C | 15 mins |
   |4˚C  | hold	 |
   
   *42˚C for SSII or 50˚C for SSIII

   *Safe stoping point, store at -20˚C*

   
   **Second Strand Synthesis**
   
30. To the 1st strand reaction add:

   |Component | volume|
   |:-:|:-:|
   | 1st strand reaction |8.4 ul |
   |Resuspension Buffer* | 1.7 ul |
   |Second Strand Master Mix to sample | 6.7 ul  |
   |Total				| 16.8 ul |

   *or Illumina In-line control

31. Incubate in thermocycler:

   |˚C | time|
   |:-:|:-:|
   |16˚C | 1 hour|
   |24˚C | hold |

32. Remove sample from thermocycler and let warm to room temperature.

   ** 1.8x AMPure**

33. Add 30 μl of well-mixed AMPure XP beads and mix by pipetting up and down until beads are in a homogenous suspension.
34. Incubate at room temperature for 15 min.
35. Place on magnetic rack for 5 min.
36. Remove and discard 45 μl of the supernatant.
37. Keep sample in magnetic rack and add 1800 μl of 80% ethanol.
38. Incubate for 30 seconds.  Remove and discard all supernatant.
39. Repeat step 37 and 38 once more for a total of two washes.
40. Add 6.7 μl Resuspension Buffer and pipet up and down until beads are in a homogenous suspension.
41. Incubate at room temperature for 2 min.
42. Place in magnetic rack for 5 min.
43. Transfer 5.83 μl of the supernatant to a new 0.2 ml PCR tube (reduce volume by 0.83 ul if adding in-line control at next step).

   **Add ‘A’ bases to 3’ ends**
   
44. To cDNA add 

   |Component 		| volume|
   |:-:|:-:|
   | cDNA	 	| 5.83 ul |
   |A-tail Mix		| 4.17 ul  |
   |Total		| 10 ul |

   
45. Incubate in thermocycler:

   |˚C | time|
   |:-:|:-:|
   |37˚C | 30 mins|
   |70˚C | 5 mins | 
   |4˚C  | hold |

   **Ligate Adapters to DNA fragments**
   
46. To A-tail reaction add:	 

   |Component 			| volume |
   |:-:|:-:|
   | A-tail reaction	 	| 10 ul |
   | Resuspension Buffer	| 0.83 ul  |
   | RNA Adapter Index		| 0.83 ul  |
   | DNA Ligase Mix		| 0.83 ul  |
   |Total		 	| 10 ul (14.16 after stop added) |

47. Incubate at 30˚C for 10 min
48. Add 1.7 μl Stop Ligase Mix

   **1.0x AMPure**

49. Add 14 μl of well-mixed AMPure XP beads and mix by pipetting up and down until beads are in a homogenous suspension.
50. Incubate at room temperature for 15 min.
51. Place on magnetic rack for at least 5 min.
52. Remove and discard 26.5 μl of the supernatant.
53. Keep sample in magnetic rack and add 180 μl of 80% ethanol.
54. Incubate for 30 seconds.  Remove and discard all supernatant.
55. Repeat steps 53 and 54 one more time.
56. Add 18.7 μl Resuspension Buffer and pipet up and down and mix by pipetting up and down until beads are in a homogenous suspension.
57. Incubate at room temperature for 5 min.
58. Place in magnetic rack for 5 min.
59. Transfer 16.7 μl of the supernatant to a new 0.2 ml PCR tube.
60. Add 16.7 μl of well-mixed AMPure XP beads.
61. Incubate at room temperature for 15 min.
62. Place on magnetic rack for at least 5 min.
63. Remove and discard 28.34 μl of the supernatant.
64. Keep sample in magnetic rack and add 200 μl of 80% ethanol.
65. Incubate for 30 seconds.  Remove and discard all supernatant.
66. Repeat steps 64 and 65 one more time.
67. Add 10.7 μl Resuspension Buffer and pipet up and down 10 times.
68. Incubate at room temperature for 5 min.
69. Place in magnetic rack for 5 min.
70. Transfer 9.5 μl of the supernatant to a new 0.2 ml PCR tube.
71. Use 1 μl to determine number of cycles to perform in following PCR amplification (see note #6).
Amplify Library by PCR
72.	Mix:	 6.67 μl Adapter ligated DNA from step 71
 1.67 μl PCR Primer Cocktail
 8.33 μl PCR Master Mix

73.	Amplify with the following PCR protocol:
a. 98˚ C for 30 seconds
b. 5 to 18 cycles of (see note #1):
	98˚ C for 10 seconds
	60˚ C for 30 seconds
	72˚ C for 30 seconds
c. 72˚ C for 5 min
d. Hold at 4˚ C
74.	Add 16.67 μl of well-mixed AMPure XP beads.
75.	Incubate at room temperature for 15 min.
76.	Place on magnetic rack for at least 5 min.
77.	Remove and discard 28.3 μl of the supernatant.
78.	Keep sample in magnetic rack and add 200 μl of 80% ethanol.
79.	Incubate for 30 seconds.  Remove and discard all supernatant.
80.	Repeat steps 78 and 79 one more time.
81.	Let the beads dry at room temperature for 2 min.
82.	Add 12 μl Resuspension Buffer and pipet up and down 10 times.
83.	Incubate at room temperature for 2 min.
84.	Place in magnetic rack for 5 min.
85.	Transfer 10 μl of the supernatant to a new 1.5 ml PCR tube.
86.	Use 1 μl for qPCR quantitation (http://ethanomics.wordpress.com/ngs-qpcr-library-quantitation-protocol/) and run 1 μl on the Bioanalyzer.

Notes:
1) This protocol assumes you know basic molecular biology practices, for instance that you should mix a reaction by pipetting after adding enzyme.
2) After thawing kit, all reagents stored at -20˚C should be mixed and then briefly spun down in microfuge before opening.  Likewise, the RNA purification beads and AMPure XP beads should be well mixed by vortexing so that they are in a homogenous solution before using.
3) Programing all the incubations into the thermocycler before you start will make your life easier.
4) The amount of starting RNA is flexible. Some cell types with low mRNA quantity will require more total RNA. Likewise, if you do not have 500 ng of total RNA, with some cell types you may be able to get away with using a lot less.
5) AMPure XP guidelines:
		a) Make sure that you achieve a homogenous solution of the beads and your sample by pipetting up and down a sufficient number of times.
		b) When removing the supernatant after the binding step, remove all but 5 μl with a P200 pipetman. Then go back, using a P20, and carefully remove as much of the last 5 μl as you can without taking any beads.
		c) When washing with 80% ethanol the beads stick to the wall of the tube better so you can remove the supernatant more quickly.  I make sure I remove all traces of ethanol by going through each tube a second time with a new pipet tip.
		d) Illumina recommends drying the beads, not only is this a waste of time but it probably reduces yield.
		e) At the elution step, when transferring the eluted DNA to a new tube, it is important not to accidentally carryover any beads. I carefully look inside the tube as I am pipetting up the eluted DNA to make sure I don’t accidentally take up any beads. Then I look at the eluted DNA in the pipet tip to see if I can see any beads. If there are, simply pipet the sample back into the tube you took it from, place it in the magnetic rack and wait a few minutes for the sample to separate again. At this step it is important to leave at least 1 μl behind, as it is not possible to remove all the liquid and not take any beads.

6) Determine number of PCR cycles to perform by using accompanying PCR cycle quantitation protocol (http://ethanomics.wordpress.com/ngs-pcr-cycle-quantitation-protocol/).
PCR Primer Quantification Mix
1.	Resuspend TruSeq PCR Primer 1 and TruSeq PCR Primer 2 in TE/10 (10 mM Tris-HCl, pH 8.0, 0.1 mM EDTA) to a concentration of 100 μM.
2.	In new tube mix: 	25 μl TruSeq PCR Primer 1 (100 μM)
25 μl TruSeq PCR Primer 2 (100 μM)
50 μl H2O
TruSeq PCR 1
AATGATACGGCGACCACCGA*G

TruSeq PCR 2
CAAGCAGAAGACGGCATACGA*G

* = phosphorothioate bond



