# reaxff-force-fields

An overview of (co-)developed ReaxFF force fields, covering material systems such as metal halide perovskites and metals.

## Available force fields

 - `IPbCs.ff (I/Pb/Cs)`: A force field trained for the description of bulk pristine and defective CsPbI~3~ and its precursors. The force field has been used to describe the phase behavior [1], stability of surfaces and grain boundaries [2], and defect migration at interfaces of CsPbI~3~ [3].
 - `IBrPbCs.ff (I/Br/Pb/Cs)`: Extension of the CsPbI~3~ parameter set to capture the behavior of mixed halide perovskites (CsPb(Br~x~I~1-x~)~3~). The force field was used to explore the effects of mixing strain on their phase behavior [4].
 - `HRu.ff (H/Ru)`: A force field trained to describe the interaction of atomic hydrogen (H) with bulk ruthenium (Ru). It was used to model the migration of H through Ru films to assess the effects of the microstructure of the Ru films [5].

## Usage

Force field files can straightforwardly be used for simulations in software packages that can run ReaxFF molecular dynamics (MD) simulations, such as: [AMS](https://www.scm.com/amsterdam-modeling-suite/reaxff/) or [LAMMPS](https://www.lammps.org/#gsc.tab=0). Please consider citing the relevant papers upon using these ReaxFF force fields.

## References

1. M. Pols *et al.*, *J. Phys. Chem. Lett.*, 12, 5519-5525 (2021), DOI:  [`10.1021/acs.jpclett.1c01192`](https://doi.org/10.1021/acs.jpclett.1c01192). [`IPbCs.ff`]  
2. M. Pols *et al.*, *ACS Appl. Mater. Interfaces*, 14, 40841–40850 (2022), DOI:  [`10.1021/acsami.2c09239`](https://doi.org/10.1021/acsami.2c09239).  
3. J. Liu *et al.*, *Nano Lett.*, 23, 10089–10096 (2023), DOI:  [`10.1021/acs.nanolett.3c03761`](https://doi.org/10.1021/acs.nanolett.3c03761).  
4. M. Pols *et al.*, *J. Phys. Chem. C*, 128, 4111-4118 (2024), DOI:  [`10.1021/acs.jpcc.4c00563`](https://doi.org/10.1021/acs.jpcc.4c00563). [`IBrPbCs.ff`]  
5. C. Onwudinanti *et al.*, *J. Phys. Chem. C*, 126, 5950–5959 (2022), DOI:  [`10.1021/acs.jpcc.1c08776`](https://doi.org/10.1021/acs.jpcc.1c08776). [`RuH.ff`]  
