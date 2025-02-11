### 3. Generation of Helical Building Blocks
The helical units are arranged in repeating patterns to create larger structures. Structural configurations of three, five, and eight repeats are analyzed to design robust protein scaffolds with predictable properties. By systematically assembling these repeats, it becomes possible to create protein-based materials with enhanced stability and versatility. The command to generate helical building blocks is:
```
/home/user/rosetta/main/source/bin/rosetta_scripts.linuxgccrelease \
    -in:file:s 8b1x_refine.pdb \
    -parser:protocol repeat_propagation.xml \
    -out:pdb
```
```
/home/user/rosetta/main/source/bin/rosetta_scripts.linuxgccrelease\
    -in:file:s 8b1x_block.pdb\
    -parser:protocol fast_design.xml\
    -out:pdb
```

![Winter_Internship_Report_-009](https://github.com/user-attachments/assets/3bfb679a-7f8b-4fcd-8652-193d40e71bd4)

Helical Building Block 

![Winter_Internship_Report_-010](https://github.com/user-attachments/assets/c5917a8d-cac6-40e4-869e-fa1319fa5c6a)

Helical Building Block with 5 repeats

