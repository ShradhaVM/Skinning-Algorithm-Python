# Skinning Algorithm using Python
**ModelExport.py**
\
The code in modelExport.py must be run in Blender. The instructions for pasting the code to Blender are given in the modelExport.py file in the beginning. 
This file gives 3 output files - polygons.csv, vertices.csv, weights.csv. These files for a Hand model are stored in the folder named 'input'.

**matCalc.py**
\
This file contains a function called recursiveMatCalc which is called in the main file skinning.py.

**skinning.py**
\
This file contains the main code. And with all the data provided in the input folder, this file can be run directly without executing any other file before it. 

**posemat.npy**
\
This file is produced by the code in skinning.py. 

****Restuls****
The result obtained is 3-D animation that follows the properties of proper rigid transformation. This
means that the relative distance is between points is preserved and the resultant pose produces a realistic bend in 3-D space.
