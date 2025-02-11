### Alpha-Helix Design
The initial step involves generating idealized alpha-helical structures. Stability is ensured by setting specific geometric constraints such as bond lengths, bond angles, and dihedrals. These helices serve as the fundamental building blocks for further modifications. The designed helices provide a base for developing structured protein scaffolds, which are essential for applications in nanotechnology and biomedical sciences. The command used to generate alpha helices in Rosetta is:
```
/home/user/rosetta/main/source/bin/rosetta_scripts.linuxgccrelease \
    -in:file:s 8b1x.pdb \
    -parser:protocol generate_helices.xml \
    -out:pdb
```

![Template Helix](https://github.com/user-attachments/assets/d5812a44-104b-4df5-b1da-85d4bd2a5f0a)
Template Helix

![Primary Helical Structure](https://github.com/user-attachments/assets/55c06775-d639-44a9-b70f-81a85c0c2383)
Primary Helical Structure
