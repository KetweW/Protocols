# BARseq + STARmap

## Timing
- Virus injection
- Day 0: Sectioning and ethanol dehydration, hybridization setup (Hybridization incubates for ~2 nights)
- Day 2: Wash, Ligation, and 1st round RCA setup (Active time: ~2-3 hrs, followed by overnight RCA incubation)
- Day 3: 1st Crosslinking, RT, 2nd Gap-filling, and 2nd RCA setup (Active time: ~4-5 hrs, followed by overnight 2nd RCA incubation)
- Day 4: Final Crosslinking and proceed to imaging

## Material

### Stock solutions
- 100% EtOH (Molecular biology grade or Anhydrous; Change new per month)
- Salmon Sperm DNA (AM9680, typically 10 mg/ml)
- 100% Formamide (Thermo - Deionized, Molecular biology grade)
- Superasin RNase Inhibitor (AM2696, typically 20 U/µl)
- RiboLock RNase Inhibitor (EO0382, typically 40 U/µl)
- RVC 200mM (S1402S - Ribonucleoside Vanadyl Complex)
- T4 DNA Ligase (M0202M)
- Phi29 DNA polymerase (EP0091 or M0269L)
- Ampligase (A0102K)
- Phusion DNA polymerase (M0530S)
- RNase H (Y9220L)
- BSPEG9 in DMSO (21582)

### Solutions

**IMPORTANT: Define all buffer compositions clearly.**

##### PBSTG (Can be stored for a long time at RT, add Salmon Sperm DNA and Superasin fresh)
| Volume  | Stock                       | Target Concentration / Notes                                  |
| ------- | --------------------------- | ------------------------------------------------------------- |
| 5 ml    | 10x PBS                     | 1×                                                            |
| 0.5 ml  | 10% Triton X-100 (v/v) stock| 0.1% v/v Triton X-100 |
| 0.375 g | Glycine powder (MW ~75.07)  | ~100mM                                                        |
| 45 ml   | Nuclease-free water |                                                               |
| 50 ml   | Total                       |                                                               |

*Immediately before use, add Salmon Sperm DNA to a final concentration of 0.1 mg/ml.*

##### PBST (Phosphate Buffered Saline + Triton X-100)
1x PBS
0.1% (v/v) Triton X-100
*Make fresh or store appropriately.*

##### PBSTw (Wash Buffer)
1x PBS
0.05% (v/v) Tween-20
*Make fresh every experiment.*

##### Specific Triton X-100 in PBS solutions (Make fresh every experiment)
-   1x PBS with 2% Triton X-100
-   1x PBS with 1% Triton X-100
-   1x PBS with 0.5% Triton X-100

---

## Procedure

### For all Superasin usage, you can increase by 50% to 100% to ensure RNA integrity during long incubations. 

### Day 0
1.  Precool sample and slides in -13°C to -15°C cryostat.
2.  Prepare metal block and cool it on dry ice.
3.  Cryosection the sample at 16 µm; use a warm finger to gently melt and adhere the section to the slide.
4.  Check the sample(every 5 sections) on the slide under a fluorescence microscope; begin collecting sections when clear cell-shaped GFP is observed.
5.  Immediately place the collected sample slide onto the cold metal block. (Continue to check GFP signal every 20-30 sections).
6.  Extra samples can be stored at -80°C directly. **Keep samples cold and dry.**
7.  Prepare 4% PFA in 1X PBS (freshly prepared or from aliquots stored at -20°C) in the hood in 50ml conical tubes.
8.  Place two slides, back-to-back, into 4% PFA with gentle rotation for 1hr at RT.
9.  Dip into 1XPBS for 3 times and mount the chamber **prevent from dry**.
10. Stepwise dehydrate the sample in 70%, 85%, and 100% EtOH (nuclease-free), 5 min each at RT.
11. Incubate in 100% EtOH for at least 1.5hr at 4°C. Cover with parafilm to prevent evaporation.
12. Wash 5 times in PBSTG (ensure smooth injection and aspiration of buffer from chamber).
13. Rehydrate in PBSTG with Superasin RNase Inhibitor (0.1-0.5 U/µl) for 15 min at RT.
14. While incubating, prepare hybridization buffer. (Recipe below for 300μl, sufficient for 2 samples; 150µl/sample).

    | Volume   | Stock                                           | Target / Notes                                               |
    | -------- | ----------------------------------------------- | ------------------------------------------------------------ |
    | 30 μl    | 20x SSC                                         | 2×                                                           |
    | 30 μl    | 100% Formamide (deionized)                      | 10% v/v                                                      |
    | 3 μl     | Salmon Sperm DNA (e10 mg/ml stock)         | 0.1 mg/ml                                                    |
    | 3 μl     | Superasin RNase inhibitor | 0.2 U/μl |
    | x μl     | Probe mix              | 10-50nM per oligo                                            |
    | 30 μl    | 200mM RVC                                       | 20mM                                                         |
    | (204-x) μl| Nuclease-free water                             | Fill to 300 μl                                               |

15. Add hybridization buffer to samples. Incubate at 40°C for over two nights (approx. 36-48 hours). (Note: This is a long incubation; if optimization is possible, consider testing 16-24h). Seal chamber well.

### Day 2
16. Remove sample from 40°C incubator. Wash 2 times in 1% PBST with Superasin (0.1-0.5 U/µl) at 37°C.
17. Wash once with 4xSSC + 1% PBST for 20 min at 37°C.

    | Volume  | Stock                  | Target    |
    | ------- | ---------------------- | --------- |
    | 60 ul    | 20x SSC       | 4×        |
    | 240 ul   | 1% PBST | |
    | 3 ul   | Superasin | 0.2U/μl |

19. Meanwhile, prepare ligation buffer. (For 10X T4 ligase buffer, limit freeze-thaw cycles to <5). (Recipe for 300µl).

    | Volume  | Stock                                                          | Target / Notes                                                                                                      |
    | ------- | -------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
    | 30 μl   | 10x T4 DNA Ligase buffer                                       | 1×                                                                                                                    |
    | 1.5 μl  | 20 mg/ml BSA                                                   | 0.1 mg/ml                                                                                                             |
    | 3 μl    | Superasin RNase inhibitor                 | 0.2 U/μl |
    | 15 μl   | T4 DNA Ligase  | 2 U/μl final                                                                                                          |
    | 250.5 μl| Nuclease-free Water                                            | Fill to 300 μl                                                                                                        |
20. Wash sample once in PBSTw to remove high salt and ensure Ligase activity.
21. Add ligation mix to samples. Incubate in a humidified chamber for 4 hr at RT.
22. Wash 2 times in PBSTw. Prepare 1st RCA buffer **on ice**.
    *dNTPs should experience <5 freeze-thaw cycles.*
    *Aminoallyl-dUTP and Phi29 buffer should experience <3 freeze-thaw cycles.*
    (Recipe for 300µl)

    | Volume  | Stock                                                                    | Target / Notes                                                                                                                               |
    | ------- | ------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------- |
    | 30 μl   | 10x Phi29 buffer                                                         | 1×                                                                                                                                           |
    | 3 μl    | 20 mg/ml BSA                                                             | 0.2 mg/ml                                                                                                                                    |
    | 12 μl   | 10 mM dNTPs                               | 0.4 mM (each)                                                                                                                                |
    | 1.5 μl  | 50 mM aminoallyl-dUTP                                                | 250 μM                                                                                                                                       |
    | 30 μl   | Phi29 polymerase  | 0.5 U/μl final                                                                                                                               |
    | 3 μl    | Superasin RNase inhibitor                       | 0.2 U/μl |
    | 30 μl   | 50% Glycerol                                                             | 5% v/v |
    | 190.5 μl| Nuclease-free Water                                                      | Fill to 300 μl                                                                                                                               |
23. Exchange RCA buffer into chamber. Incubate on ice for 15 min, then at RT for 10 min, and finally in a 25°C incubator overnight (approx. 16-18 hours).

### Day 3
23. Remove sample from incubator. **Wash slowly** 2 times using PBSTw.
24. Crosslink the 1st RCA product. Prepare Crosslinking buffer: (Recipe for 300µl)
  *BSPEG9 are 250mM stocks in DMSO, use the aliquote no longer than 3 weeks*

    | Volume | Stock                                                                          | Target / Notes                                                                                                                             |
    | ------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
    | 60 μl  | BSPEG9 stock in DMSO | 50mM final BSPEG9 |
    | 30 μl  | 200 mM RVC                                                                     | 20mM                                                                                                                                       |
    | 210 μl | PBST | Fill to 300μl                                                 |
    
    Incubate in Crosslinking buffer for 1 hr in a humidified chamber at RT.
26. Wash 1X in 1M Tris-HCl pH 8.0. Then, incubate in 1M Tris-HCl pH 8.0 with Superasin RNase Inhibitor (0.2 U/µl final) for at least 30 min at RT.
27. Wash 2 times with PBSTw.
28. Prepare RT buffer. (Limit freeze-thaw of RT buffer to <=2 times). (Recipe for 300µl)

    | Volume | Stock                                                            | Target / Notes                                      |
    | ------ | ---------------------------------------------------------------- | --------------------------------------------------- |
    | 60 μl  | 5x RT buffer                                | 1×                                                  |
    | 3 μl   | 20 mg/ml BSA                                                     | 0.2 mg/ml                                           |
    | 7.5 μl | RiboLock RNase inhibitor                    | 1 U/μl                                              |
    | 15 μl  | 10 mM dNTPs                                                      | 0.5 mM (each)                                       |
    | 3 μl   | BC LNA RT primer (XC1215)    | 1μM                                                 |
    | 30 μl  | RevertAid H Minus M-MuLV RT               | 20 U/μl                                             |
    | 181.5 μl| Nuclease-free Water                                              | Fill to 300 μl                                      |
    
    Add RT buffer to samples. Incubate at 37°C for at least 5 hr. (Note: 5hr is a long RT; if optimization is possible, consider testing 1-2h).
30. Crosslink the RT product using the Crosslinking buffer recipe from Step 24 (but **omit RVC**). Incubate for 1 hr (or specify duration) in a humidified chamber at RT.
31. Wash 1X in 1M Tris-HCl pH 8.0. Then, incubate in 1M Tris-HCl pH 8.0 for at least 30 min at RT.
32. Gap Filling. Prepare Gap-filling buffer: (Recipe for 300µl)

    | Volume  | Stock                                                                               | Target / Notes                                                                                                                                            |
    | ------- | ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | 30 μl   | 10x Ampligase buffer                                                                | 1×                                                                                                                                                        |
    | 7.5 μl  | 2M KCl                                                                              | 50mM |
    | 0.3 μl  | /5p/BC padlock (XC1164)                         | 0.1μM                                                                                                                                                     |
    | 1.5 μl  | 10 mM dNTPs                                                                         | 0.05 mM (each)                                                                                                                                            |
    | 30 μl   | 50% Glycerol                                                                        | 5% v/v |
    | 60 μl   | 100% Formamide                                                                      | 20% v:v                                                                                                                                                   |
    | 1.5 μl  | Ampligase | 0.5 U/μl final |
    | 7.5 μl  | RiboLock RNase inhibitor                                      | 1 U/μl                                                                                                                                                    |
    | 0.15 μl | Phusion DNA Polymerase                                         | 0.001 U/μl                                                                                                                                                |
    | 24 μl   | RNase H                                                        | 0.4 U/μl                                                                                                                                                  |
    | 137.55 μl| Nuclease-free Water                                                                 | Fill to 300 μl                                                                                                                                            |
    
    Add Gap-filling buffer to samples. Incubate for 5 min at 37°C, then 45 min at 45°C. **Timing is stringent.**
33. Wash 2 times in PBSTw.
34. Prepare final (2nd) RCA buffer: (Recipe for 300µl)

    | Volume  | Stock                                                                    | Target / Notes                                                                                                                               |
    | ------- | ------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------- |
    | 30 μl   | 10x Phi29 buffer                                                         | 1×                                                                                                                                           |
    | 3 μl    | 20 mg/ml BSA                                                             | 0.2 mg/ml                                                                                                                                    |
    | 7.5 μl  | 10 mM dNTPs                                                              | 0.25 mM (each)                                                                                                                               |
    | 0.75 μl | 50 mM aminoallyl-dUTP                                                | 125 μM                                                                                                                                       |
    | 30 μl   | Phi29 polymerase  | 0.5 U/μl final                                                                                                                               |
    | 30 μl   | 50% Glycerol                                                             | 5% v/v |
    | 198.75 μl| Nuclease-free Water                                                      | Fill to 300 μl                                                                                                                               |
    
    Add 2nd RCA buffer to samples. Incubate at 25°C overnight (approx. 16-18 hours).

### Day 4
33. Wash **slowly** 2 times in PBSTw.
34. Crosslink with the Crosslinking buffer recipe from Step 24 (but **omit RVC**). Incubate for 1 hr (or specify duration) in a humidified chamber at RT.
35. Wash 1X in 1M Tris-HCl pH 8.0. Then, incubate in 1M Tris-HCl pH 8.0 for at least 30 min at RT.
36. Proceed to sequencing (and subsequent imaging steps).

