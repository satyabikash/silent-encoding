This notebook exihibit a way to calculate(or compare) the rmsd between two structures but in different file format.In general the pdb file can be easily handeled by the MDAnalysis modules, but the silent file(rosetta specific compressed protein structure data) needed to be extracted to the respective pdb file and then can be used for comparison.
Hence, to avoid this extra work of extracting and then calculating directly getting the structural information of the motif and doing the necessary seems to me more convinent. 
There's no unified way to do so from rosetta documentations, there are many rmsd calculations in the documentations but those goes above head !. Therefore this notebook seems to do the work for me.
