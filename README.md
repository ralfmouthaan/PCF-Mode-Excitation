# PCF-Mode-Excitation


Scripts used for paper on mode excitation in arbitrary geometry fibres. This paper uses a finite difference frequency domain (FDFD) model to calculate what modes are guided in the fibre to hand. A direct search (DS) algorithm is then used to generate holograms capable of exciting these modes. An experimental demonstration is given. Two programs are included:

a) An FDFD model adapted for waveguide geometries. This is in the folder "Waveguide FDFD Solver". This folder has the main FDFD engine (ModeSolverFD.m), and an example for setting up a problem (ErlangenPCF.m).

b) A DS algorithm for generating holograms for exciting discrete modes. This is in the folder "Fibre DS Hologen". This folder has the main DS engine (DirectSearchSymmetryBinary.m). An example for setting up the problem is included (Single_LP_Hologen.m). This example generates a step index fibre LP mode (using LP_Mode.m), and generates the hologram for this. 

A pre-submission copy of the submitted journal paper is included, and will be updated with a preprint copy once the paper has been accepted.