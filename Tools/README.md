# Tools

Here you can find some little programs. This ever-expanding collection serves to complete small tasks and can also serve as examples for working with rdkit and other Python libraries.



## Molfile-Viewer

[Molfile-viewer](Molfile-viewer.ipynb) is a program (Jupyter Notebook) that displays a molecule from an MDL Molfile. A few examples are located in the examples folder.

The program reads a Molfile, creates a temporary image of the molecule with numbering, and can optionally convert 3D coordinates to 2D coordinates to produce a better representation. Additionally, it currently displays the Mol block of the rdkit molecule object in another code block. I used this to explore the issues with reading Mol files with rdkit. For example, bond type 4 (aromatic) is not read or represented as delocalized. Rdkit replaces the aromatic bonds with alternating single and double bonds (b-acid3.mol demonstrates this).