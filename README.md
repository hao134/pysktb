# pysktb
Scientific Python package for solving Slater Koster tight-binding hamiltonian
                            

A python package in development for creating and solving slater koster tight-binding hamiltonians for various 1D 2D and 3D systems.

### Features

  - Generate s,p,d interactions in any given lattice
  - Specify range of interaction with more then Nearest neibghor
  - Spin Polarized calculations
  - Spin orbit coupling *(only for p orbitals as of now)*
  - Plot orbital weighted colorplots
  - Integration with [pymatgen](https://pymatgen.org) structres 



### Installation
 1. Copy the files _params.py and pysktb.py to the working directory
 2. Import them and use !

 
### Examples

Example usage shown in 	[examples.ipynb](./examples/examples.ipynb)
1. 1D chain of sp (example of 1D topological Crystiline insulator *SSH*)
  <img src="./examples/sp-chain.png" style="max-height: 70px; max-width: 70px;" >
  - with orbital projection on s
  <img src="./examples/sp-chain-proj.png" style="max-height: 70px; max-width: 70px;" >
2. Graphene and band colorplot in BZ
  <img src="./examples/graphene.png" style="max-height: 70px; max-width: 70px;" >
3. Buckled antimony Sb 
   - preprint of Dirac cones merging in 2D Sb https://arxiv.org/abs/1912.03755
   <img src="./examples/Sb-flat.png" style="max-height: 70px; max-width: 70px;" >
   - preprint of Higher Order Topological states in 2D Sb https://arxiv.org/abs/2003.12656
   <img src="./examples/Sb_buckled.png" style="max-height: 70px; max-width: 70px;" >
  
### Features to be added
   - Spin Orbit Coupling for d,f
   - Bogoliubov-de-Gennes (BdG) solutions for the given system for Superconductivity 
   - Interface with [ASE](https://wiki.fysik.dtu.dk/ase/) structures
   - Create finite structures and slabs for Topological calculations within the code *(requires pymatgen rightnow)*
   - Berry phase calculation (high on priority)
   - ~~Greens function DOS~~ (added normal DOS)
   - Convert all operations to sympy, so that one can ouput analytical Tightbinding matrix elements for ease of access 

