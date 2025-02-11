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
![Winter_Internship_Report_-007](https://github.com/user-attachments/assets/b758182f-2f04-48ec-8718-c465be74d2cf)
Modeled Loop

![Winter_Internship_Report_-008](https://github.com/user-attachments/assets/da0252eb-eeb0-4050-8db8-39387c049071)

Refined Loop Structure
