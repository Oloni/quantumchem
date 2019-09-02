# quantumchem
searching Open Access literature for quantum chemistry (inspiration Leonie Mueck)

## miniproject at eLife Sprint Cambridge 2019
petermr is offering miniproject/s in searching the Open Access Literature on any subjects in EuropePMC or possibly beyond.

Leonie Mueck suggested "quantum chemistry", this is a prototype

## issues
Github issues used to manage the project.
### dictionaries

## dictionaries
We need dictionaries for key concepts/ terms. Suggest:
### Overall method (DFT, Hartree Fock, Coupled Cluster etc.)
### Multireference or single reference problem/method
### basis-sets
### functionals
### software package
### Property being calculated (energies, geometries, chemical shifts...)
### Open Science practices (do they share xyz files, input files?)
### Type of molecule or material (protein, transition metal complex etc.)
### If multireference method: size of active space
### Comparison to experimental data?

## corpora
Initial corpus of 100 EPMC papers:
```
getpapers -x -o qchem -q "quantum chemistry" -k 100
```

## initial dataTable scoping
```
 ami-search -p qchem/ --dictionary country funders
```
 

