#Illumina Truseq mRNA stranded kit protocol, one-third reaction volumes

  *This great idea was not my idea, reproduced from [Ethan Ford](http://ethanomics.wordpress.com/truseq-rna-library-preparation-kit-v2-using-one-third-the-reagents/) with modifications* 


**PolyA select mRNA, fragment and prime for 1st strand synthesis**

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
9. Add 66.7 μl of Bead Washing Buffer and pipette up and down until beads are in a homogenous suspension.
10. Place the sample back in the magnetic rack for 5 min.
11. Remove and discard all the supernatant.
12. Add 16.7 μl of Elution Buffer and pipette up and down until beads are in a homogenous suspension.
13. Incubate in thermocycler:

   |˚C | time|
   |:-:|:-:|
   |80˚C | 2 min|
   |25˚C | hold |

14. Remove sample from thermocycler when it reaches 25˚ C and keep at room temp.
15. Add 16.7 μl of Bead Binding Buffer and pipette up and down until beads are in a homogenous suspension.
16. Incubate at room temperature for 5 min.
17. Place sample in magnetic separator for 5 min.
18. Remove and discard all supernatant.
19. Remove sample from rack.
20. Add 66.7 μl of Bead Washing Buffer and pipette up and down until beads are in a homogenous suspension.
21. Place sample in magnetic separator for 5 min.
22. Remove and discard all supernatant.
23. Add 6.5 μl Elute, Prime, Fragment Mix and pipette up and down until beads are in a homogenous suspension.
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
37. Keep sample in magnetic rack and add 180 μl of 80% ethanol.
38. Incubate for 30 seconds.  Remove and discard all supernatant.
39. Repeat step 37 and 38 once more for a total of two washes, use a fine point tip to remove all ethanol after the second wash
40. Dry at 30˚C to 2-3 mins.
40. Add 6.7 μl Resuspension Buffer and pipette up and down until beads are in a homogenous suspension.
41. Incubate at room temperature for 5 min.
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
55. Repeat steps 53 and 54 one more time use a fine point tip to remove all ethanol after the second wash
40. Dry at 30˚C to 2-3 mins.
56. Add 18.7 μl Resuspension Buffer and pipette up and down and mix by pipetting up and down until beads are in a homogenous suspension.
57. Incubate at room temperature for 5 min.
58. Place in magnetic rack for 5 min.
59. Transfer 16.7 μl of the supernatant to a new 0.2 ml PCR tube.
60. Add 16.7 μl of well-mixed AMPure XP beads.
61. Incubate at room temperature for 15 min.
62. Place on magnetic rack for at least 5 min.
63. Remove and discard 28.34 μl of the supernatant.
64. Keep sample in magnetic rack and add 200 μl of 80% ethanol.
65. Incubate for 30 seconds.  Remove and discard all supernatant.
66. Repeat steps 64 and 65 one more time use a fine point tip to remove all ethanol after the second wash
40. Dry at 30˚C to 2-3 mins.
67. Add 10.7 μl Resuspension Buffer and pipette up and down 10 times.
68. Incubate at room temperature for 5 min.
69. Place in magnetic rack for 5 min.
70. Transfer 9.5 μl of the supernatant to a new 0.2 ml PCR tube.

    **qPCR quantify the library pre-PCR enrichment**

71. Use 1 μl to determine number of cycles to perform in the following PCR amplification.
72. Dilute 1ul of library into 9 ul of water
73. Using the Kapa qPCR kit for Illumina run 10uL reactions in technical duplicate and determine the pM of the libraries.
74. Use the following formula to calculate the cycles needed, aim for 20-30nM, ideally then normalise DNA input based on lowest concentration sample so all samples get the same PCR cycles. Alternatively, normalised post-PCR.


    ```
    ([conc]) x d x ex) = 20,000
    
    [conc] = pM of pre-PCR library
    d	 = dilution of library postPCR cleanup
    e	 = PCR efficiency
    
    eg. Sample#1:
    235pM pre-PCR concentration 
    will use 6.67 ul in PCR 
    re-suspend PCR product in a volume of 11ul after cleanup
    PCR efficiency in qPCR was 1.94

    ([235] x (6.67/11) x 1.94x = 20000
    Cycles = log(1.94)(20000/235x0.61)
    Cycles = 7.46 cycles

    ```
 
    **Amplify Library by PCR**
    
72. Mix:	 


   |Component 			| volume |
   |:-:|:-:|
   | 6.67 μl Adapter ligated DNA	 	| 6.7 ul |
   | PCR Primer Cocktail	| 1.7 ul  |
   | PCR Master Mix		| 8.3 ul  |
   |Total		 	| 16.7 ul |

73.	Amplify with the following PCR protocol:

    |step	|	1	|	2	|	3	|	4	|	5	|7	    |
    |:------|:--------------|:--------------|:--------------|:--------------|:--------------|:------|
    |temp	|98		|98		|60		|72		|*Go to 2 x 34 times*|	4 |
    |min	|0:30		|0:10		|0:30		|0:30		|		|hold|

74. Take 1 ul and dilute into 9 ul water and run on GXII DNA-HS.  If cycle number is insufficient, run more cycles.  *Note that the upper maker progressively runs worse with each sample, seemingly due to the Illumina PCR buffer (runs fine after clean-up). This means that after the first few samples the reported conc/molarity is totally bogus, although the smears seem resonable relative to each other.*

    **AMPure 1.0x**

74. In a fresh tube, add and equal volume of well-mixed AMPure XP beads (probably 15.5 ul) to the PCR.
76. Place on magnetic rack for at least 5 min.
77. Remove and discard 28.3 μl of the supernatant.
78. Keep sample in magnetic rack and add 200 μl of 80% ethanol.
79. Incubate for 30 seconds.  Remove and discard all supernatant.
80. Repeat steps 78 and 79 one more time use a fine point tip to remove all ethanol after the second wash
40. Dry at 30˚C to 2-3 mins.
81. Let the beads dry at room temperature for 2 min.
82. Add 11 μl Resuspension Buffer and pipette up and down 10 times.
83. Incubate at room temperature for 2 min.
84. Place in magnetic rack for 5 min.
85. Transfer 9.8 μl of the supernatant to a new 1.5 ml PCR tube.


   **Quantify and pool**
    
86. Use 1 μl for GXII DNA-HS and 1ul for the Qubit DNA-HS.





