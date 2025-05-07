# BARseq + STARmap

## Timing
- Virus injection
- Day 0: Sectioning and ethanol dehydration, hybridization
- Day 2: Wash, Ligation and 1st round RCA(~6hrs with 4hr long incubation)
- Day 3: 1st Crosslinking, RT, 2nd Gap-filling, 2nd RCA(9hr with 5 hr long incubation)
- Day 4: Crosslinking and proceed to imaging

## Material

### Stock solutions
- 100% EtOH(Change new per month)
- Salmon Sperm DNA (AM9680)
- 100% Formamide(Thermo)
- Superasin RNase Inhibitor (AM2696)
- RiboLock RNase Inhibitor (EO0382)
- RVC 200mM (S1402S)
- T4 DNA Ligase (M0202M)
- Phi29 DNA polymerase (EP0091 or M0269L)
- Ampligase (A0102K)
- Phusion DNA polymerase (M0530S)
- RNase H (Y9220L)
- BSPEG9 in DMSO (21582)

### Solutions

##### PBSTG (Can be store in long time at RT)
| Volume  | Stock                   | Target    |
| ------- | ----------------------- | --------- |
| 5 ml    | 10x PBS                 | 1×        |
| 0.5 ml  | 10x Triton              | 1% v/v    |
| 0.375 g | Glycine powder          | 100mM     |
| 1:100 before use | Salmon Sperm DNA        |      |
| 45 ml   | Water (MilliQ or Fancy) |           |
| 50 ml   | Total                   |           |

### 2%, 1% and 0.5% PBST(Make fresh every experiment)

## Procedure

### Day 0
1. Precold sample and slides in -13C~-15C cryostat.
2. Prepare metal block and cool it in dry ice.
3. Cryosection the sample at 16 μm, use hand to melt and stick the sample onto slide.
4. Check the sample on the slide under fluorescence microsope, starting collect when observing clear cell-shaped GFP
5. Immediatelly put the collected sample onto metal block.(Still, check the GFP every 15-20 sections)
6. Extra samples can be stored in -80C directly. **keep sample cold and dry.**
7. Prepare 4% PFA in 1XPBS in hood in 50ml conical tubes.
8. Place two slides, back to back, into 4% PFA, gentally rotate for 1hr.
9. Wash 3 times in 1XPBS and mount the chamber.
10. Step dehydrate the sample in 70%, 85% and 100% EtOH, 3min each.
11. Incubate in 100% EtOH for at least 1.5hr at 4C. Cover with parafilm to prevent dry.
12. Wash 5X in PBSTG, ensure smooth injection and aspiration of buffer from chamber
13. Rehydrate in PBSTG with Superasin for 15min at RT
14. While incubating, prepare hybridization buffer.(300μl is for 2 samples)

| Volume  | Stock                  | Target    |
| ------- | ---------------------- | --------- |
| 30 μl  | 20x SSC                | 2×        |
| 30 μl  | Formamide              | 10%       |
| 3 μl  | SSDNA    | 1:100 |
| 3 μl  | Superasin RNase inhibitor | 1:100     |
| x μl  | probe mix | 10-50nM per oligo     |
| 30 μl  | 200mM RVC               | 20mM        |
| 204-x μl | water         | Fill to 300 μl |

15. Incubate at 40C for over two nights

### Day 2
16. Remove sample from 40C incubator, wash 2 times in PBST with Superasin at 37C.
17. Wash once with 4xSSC + PBST for 20min at 37C
18. Meanwhile prepare ligation buffer, for 10X buffer, freeze-thaw less than 5 times.

| Volume  | Stock                  | Target    |
| ------- | ---------------------- | --------- |
| 30 μl    | 10x T4 ligase buffer   | 1×        |
| 1.5 μl  | 20 mg/ml BSA           | 0.1 mg/ml |
| 3 μl  | Superasing RNase inhibitor | 0.4 U/μl  |
| 15 μl  | T4 DNA ligase          |           |
| 250 μl   | Water                  | Fill to 300 μl |
19. Wash sample once in PBSTw(remove high salt to ensure Ligase activity)
20. Incubate in wet condition for 4hr at RT
21. Wash 2X in PBSTw and prepare RCA buffer **on ice**

| Volume  | Stock                             | Target    |
| ------- | --------------------------------- | --------- |
| 30 μl    | 10x Phi29 buffer              | 1×        |
| 3 μl  | 20 mg/ml BSA                      | 0.2 mg/ml |
| 12 μl | 10 mM dNTPs                       | 0.4 mM   |
| 1.5 μl  | **50 mM** aminoallyl-dUTP          | 250 μM     |
| 30 μl  | Phi29 polymerase | 0.2 U/μl  |
| 3 μl  | Superasing RNase inhibitor            | 0.4 U/μl  |
| 30 μl    | 50% Glycerol              | 5%        |
| 200 μl | Water                             |   Fill to 300 μl   |
22. Exchange the RCA buffer into chamber and incubate on ice for 15min and the RT for 10min, 25C incubator overnight

### Day 3
23. Remove sample from incubator and **wash slowly** using PBSTw for 2 times
24. Crosslink the RCA product in Crosslinking buffer: for 1hr at wet RT environment

| Volume  | Stock                             | Target    |
| ------- | --------------------------------- | --------- |
| 60 μl    | BSPEG 9 stock              | 1×        |
| 30 μl | 200 mM RVC  | 20mM   |
| 210 μl  | PBST          | Fill to 300μl |
25. Wash 1X in 1M Tris-HCL pH 8.0 and incubate in 1M Tris-HCL pH 8.0 **with 1:100 Superasin** for at least 0.5hr.
26. Wash 2X with PBSTw.
27. Prepare RT buffer: incubate at 37C for at least 5hr

| Volume  | Stock                  | Target    |
| ------- | ---------------------- | --------- |
| 60 μl    | 5x RT buffer   | 1×   |
| 3 μl  | 20 mg/ml BSA           | 0.2 mg/ml |
| 7.5 μl  | RiboLock RNase inhibitor |  |
| 15 μl | 10 mM dNTPs                       | 0.5 mM   |
| 3 μl  | BC LNA RT primer (XC1215)          |  1μM   |
| 30 μl  | RevertAid H Minus M-MulV RT          |           |
| 180 μl   | Water                  | Fill to 300 μl |
28. Crosslink the RT product in Crosslinking buffer above, no need RVC
29. Wash 1X in 1M Tris-HCL pH 8.0 and incubate in 1M Tris-HCL pH 8.0 for at least 0.5hr.
30. Gap Filling using following gap-filling buffer: 5min at 37C and 45min at 45C, **time is stringent**

| Volume  | Stock                             | Target    |
| ------- | --------------------------------- | --------- |
| 30 μl    | 10x Ampligase buffer              | 1×        |
| 7.5 μl  | 2M KCL         | 50mM |
| 0.3 μl  | /5p/BC padlock (XC1164)          |  0.1μM   |
| 1.5 μl | 10 mM dNTPs                       | 0.05 mM   |
| 30 μl    | 50% Glycerol              | 5%        |
| 60 μl  | 100% Formamide   | 20% v:v |
| 1.5 μl  | Ampligase | 0.2 U/μl  |
| 7.5 μl  | RiboLock RNase inhibitor      | 0.4 U/μl  |
| 0.15 μl  | Phusion |  |
| 24 μl  | RNase H |  |
| 120 μl | Water      |   Fill to 300 μl   |

31. Wash 2X in PBSTw
32. Prepare final RCA buffer: 25C overnight

| Volume  | Stock                             | Target    |
| ------- | --------------------------------- | --------- |
| 30 μl    | 10x Phi29 buffer              | 1×        |
| 3 μl  | 20 mg/ml BSA                      | 0.2 mg/ml |
| 7.5 μl | 10 mM dNTPs                       | 0.25 mM   |
| 0.75 μl  | **50 mM** aminoallyl-dUTP          | 125 μM     |
| 30 μl  | Phi29 polymerase | 0.2 U/μl  |
| 30 μl    | 50% Glycerol              | 5%        |
| 200 μl | Water                             |   Fill to 300 μl   |

### Day 4
33. Wash **slowly** 2X in PBSTw
34. Crosslink with crosslinking buffer with no RVC added
35. Wash 1X in 1M Tris-HCL pH 8.0 and incubate in 1M Tris-HCL pH 8.0 for at least 0.5hr.
36. Proceed to sequencing




