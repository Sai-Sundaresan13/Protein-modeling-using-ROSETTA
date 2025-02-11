### 2. Loop Modeling
Loop modeling is employed to ensure proper connectivity between adjacent helices. Blueprint files containing sequence and connectivity information are created and refined. Computational refinement techniques are applied to minimize steric clashes and improve structural stability. This step is critical in maintaining the integrity and functionality of the designed protein structures. The command for loop modeling is:
```
/home/user/rosetta/main/tools/remodel/getBluePrintFromCoords.pl \
    -pdbfile 8b1x_01.pdb
    -chain A > 8b1x_01.remodel
```
Make Necessary changes to the .remodel file by adding the loops codes

```
/home/user/rosetta/main/source/bin/remodel.linuxgccrelease \
    @flags/flag_missing_loop
```
```
/home/user/rosetta/main/source/bin/loopmodel.linuxgccrelease \
    @flags/flag_refine_loop
```

![Winter_Internship_Report_-009](https://github.com/user-attachments/assets/3bfb679a-7f8b-4fcd-8652-193d40e71bd4)
Helical Building Block 

![Winter_Internship_Report_-010](https://github.com/user-attachments/assets/c5917a8d-cac6-40e4-869e-fa1319fa5c6a)
Helical Building Block with 5 repeats

