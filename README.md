## The objectives of this learning:
1. Understand and demonstrate the importance of proper protein preparation and reliabilityanalysis
2. Recall basic sequence analysis workflows in the Multiple Sequence Viewer/Editor
3. Recall and apply knowledge of protein surface analysis
4. Recall and apply knowledge of antibody structure prediction and humanization
5. Recall and apply knowledge of protein-protein docking by setting up an antibody-antigendocking job and analyzing the results
6. Recall and apply knowledge of residue scanning by running an alanine scanning job andanalyzing the results
7. Complete a case study covering a particular antibody engineering; 
8. Evaluate antibody-antigenbinding, justify mutation selection and compute MM-GBSA binding energy predictions for the proposed mutants


## Antibodies
Antibodies, also known as Immunoglobulins (Ig) are gamma globulin proteins, primarily found in the blood of vertebrates. These glycoproteins serve as a critical component of the immune system when the host fails to activate alternative compliment pathways or phagocytic cells in response to invading microorganisms or other antigens. The incredible specificity with which immunoglobulins bind to an antigen is based upon structural complementarity between the antigen and antibody heavy and light chains.

When a foreign antigen binds to a B-lymphocyte (B-cell), it activates the B-cell, and upon stimulation by helper T-cells, undergoes clonal proliferation and B-cell maturation into antibody forming plasma cells. Each plasma cell is programmed to make an antibody of a single specificity, which it releases into the blood.

#### Structure
The basic functional unit of an antibody is an immunoglobulin monomer, but antibodies secreted from plasma cells are typically dimeric with occasional higher order structures. Typical secreted antibodies have a basic four-peptide structure of two identical heavy chains and two identical light chains joined together by interchain disulfide bonds, forming a “Y” shaped molecule.

The disulfide bonds are positioned within a flexible region called the hinge region, which seperates the lobes of the antibody from one another and provides ample flexibility to bind antigens effectively. [1] Each domain (2 heavy and 2 light) contain between 70-110 amino acids and are classified into different categories according to size and function. [4] Both domains, heavy and light, contain variable and constant regions that are crucial to antibody function.

#### Heavy Chain
There are five types of immunoglobulin heavy chains, in mammals, α, δ, ε, γ, and μ, and give rise to the five unique classes or isotypes of antibodies, IgA, IgD, IgE, IgG, and IgM, which differ in size and composition. Each heavy chain has a constant region and variable region. The constant region is identical in all antibodies of the same isotype, but differ in antibodies of different isotypes; i.e. all IgA have the same sequence in their heavy chain constant region, but these constant regions differ between IgA and IgD, etc. [6] The α, δ, and γ heavy chains have a constant region composed of three tandem immunoglobulin domains while heavy chains ε and μ contain four. The variable region of the heavy chain in antibodies is different for all antibodies created by different B-cells.

#### Light Chain
Every antibody contains two light chains that are identical to each other. There are two types of immunoglobulin light chains in mammals, labeled lambda and kappa, with only one represented in each antibody. Each light chain has one constant domain followed by one variable domain, with a total length of about 215 amino acids.

#### Variable Regions
The Fab region (Fragment, Antigen Binding region) is composed of one constant and one variable domain from each heavy and light chain of the antibody. It is the part of the antibody that gives it its famous “Y” shape.[8] Held within the Fab region is the variable domain, also known as the Fv region.[9] Within the Fv region lie “hypervariable regions,” positioned at one end of the variable domain where they form parts of the Beta-turn loops and are clustered close to each other in space. The clustering of the hypervariable loops at the tips of the variable regions where the antigen-binding site is located makes them perfect candidates for antigen recognition. [1]The sequence heterogeneity of the three heavy and three light chain hypervariable loops creates significant antigen specificity diversity through variations in the binding surface nature and shape. Each hypervariable region can be viewed as an independent structure contributing to the complementarity of the biding site and antigen and is often referred to as a complementarity determining region (CDR).

#### Constant Regions
The remaining part of the antibody, namely the Fc region, does not play a role in binding the antigen, but rather is responsible for modulating the immune systems response to the formation of an antibody-antigen complex. The Fragment Crystallizable (Fc) region is composed of two heavy chain constant regions that are isotype specific. [11] Antibodies are glycoproteins because of glycosylation at conserved positions in their Fc regions. This glycosylation is a critical component determing the rate of antibody clearance form the body.[12] Once an antibody binds to an antigen, the Fc region binds to Fc receptors, among other proteins, to mediate a host of different physiological responses ranging from oposonization, to degranulation of mast cells, to the release of cytokines and cytotoxic molecules, etc. resulting in the destruction of the pathogen. [13] Depending on the class of antibody, as dictated by the identity of the Fc region, the antibody half-life and distribution throughout the body varies. Further, since Fc receptors are antibody isotype specific, the type of immune response is dependent on the type of Fc region on the immunoglobulin, allowing for different immune responses to the same pathogen if necessary
