## NDPK modelling

This package implements code and results presented in the below paper

```
.
├── README.md
├── LICENSE
├── analysis
│    ├── interaction_map.html    
│    ├── interaction_map.ipynb           # Jupyter notebook to plot complex interaction map
│    ├── mmgbsa.in
│    ├── mmgbsa.sh                       # bash script to run MMGBSA calculation
│    ├── mmgbsa_decomposition_nme1.dat
│    ├── mmgbsa_nme1.out
│    ├── nme1_com_dry.prmtop
│    ├── nme1_lig_dry.prmtop
│    ├── nme1_rec_dry.prmtop
│    ├── plot
│    │    ├── interaction.in
│    │    ├── node_nme1_ab.ps
│    ├── rmsd_xmgrace.bfile
├── simulation
    ├── a_equilibrium.sh                # bash script to run system equilibration
    ├── b_production.sh                 # bash script to run molecular dynamics
    ├── c_lowest_energy_structure.sh    # bash script for output lowest energy PDB structure
    ├── c_mmgbsa_topology.sh            # bash script to generate prmtop files for MMGBSA calculation
    ├── c_nme1_prod_200.crd
    ├── c_nme1_prod_200.rst
    ├── c_prod_200.out
    ├── c_rmsd.sh                       # bash script for output structure backbone RMSD & RMSF
    ├── c_total_enegy.sh                # bash script for output total energy report file
    ├── nme1.solv.prmtop
    ├── parameter
        ├── a_minimization_1.in
        ├── a_minimization_2.in
        ├── b_equilibrium_1.in
        ├── b_equilibrium_2.in
        ├── b_equilibrium_3.in
        ├── c_production_1.in
        ├── d_mmgbsa_com.in
        ├── d_mmgbsa_lig.in
        ├── d_mmgbsa_rec.in
```

### Modelling dynamics of human NDPK hexamer structure, stability and interactions
Lim YY and Natarajan KN.  _(unpublished)_

### Contact
Kedar Natarajan (_kenana@dtu.dk_)


