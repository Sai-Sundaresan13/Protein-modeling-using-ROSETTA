### 4. Structural Optimization and Refinement
The designed protein blocks undergo structural relaxation to identify the lowest-energy conformations. Iterative minimization steps optimize side-chain packing and backbone conformations. Multiple runs are performed to ensure reproducibility and structural integrity, ensuring that the designed protein structures remain stable under different conditions. The relaxation protocol is run using the command:
```
/home/user/rosetta/main/source/bin/relax.default.linuxgccrelease \
    -s 8b1x_block_fd.pdb \
    -out:suffix _relaxed \
    @flags/general_relax_flags
```


