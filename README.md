# WaterDock2.0

This is a Command line interface of WaterDock2.0

To run

python waterdock2.py proteinfile.pdbqt ligandfile.pdb

Dependencies

-- MDAnalysis (version >= 0.13)

-- numpy (any version compatible with your MDAnalysis build)

-- scipy (version does not matter)


FILE FORMATS

Protein File -- *pdbqt*

Ligand File -- *pdb/mol2*
Check to ensure that Hydrogens are added correctly. 

KNOWN ISSUES

The MDAnalysis package struggles with the 'CONECT' information in the *pdb* files.
Make sure to remove them from the ligand pdb files supplied.
WaterDock2.0 is automatically guesses connectivity information using a procedure similar to the one used by *Antechamber* of the *AMBER* package. 
