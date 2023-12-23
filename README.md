OrgoPuzzle by Trenton W, 2023. 

Part 0: Introduction and Concept
This is a project designed to follow an undergraduate organic chemistry course by visualizing reactions. Resources that already exist to solve organic chemistry reactions include OrgoSolver and ACE mechanism calculator. 
The unique part of this project will be the ability to highlight reaction sites and animate the reactions as they occur. Users will be able to see how the molecule moves over the course of the reaction.
For organic chemistry courses, synthesis problems are often a puzzle with a few similar solutions. This project aims to create an organic chemistry puzzle game. 

Part 1: Line-Angle Visualization
Visualization will depend on the open source cheminformatics software rdkit. Atom locations will be taken from rdkit functions and visualized with a custom method in line-angle projections. 
The back-end of this project will always think in line-angle, then other projections can be translated from that information.
Molecules will be created following SMILES standards for naming molecules. 

Part 2: Identifying Molecule Properties
Functional groups, stereocenters, etc will be detected and reported by rdkit functions and the visualization will be modified to highlight or point out those properties.

Part 3: Preparing Simple Reactions
One-step reactions between simple reactants can be predicted as long as functional groups are known.

Part 4: Further Steps...
Features include more complex reactions, a user interface for selecting/creating reactants, moving between different projections.... 

-----------------------------------------------------------------
Written 12/23/23
-----------------------------------------------------------------
