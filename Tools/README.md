# Tools

Here you can find some little programs. This ever-expanding collection serves to complete small tasks and can also serve as examples for working with rdkit and other Python libraries.



## Molfile-Viewer

[Molfile-viewer](Molfile-viewer.ipynb) is a program (Jupyter Notebook) that displays a molecule from an MDL Molfile. A few examples are located in the examples folder.

The program reads a Molfile, creates a temporary image of the molecule with numbering, and can optionally convert 3D coordinates to 2D coordinates to produce a better representation. 

Now it use pythons tempfile library for the image generation and looks automatically for explicit hydrogens and remove this from image when exists.