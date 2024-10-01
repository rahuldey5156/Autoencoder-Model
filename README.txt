The datafile contains the dihedral angles of protein in the monolayer and bilayer environment at each frame.
The phi and psi angles are converted to sine and cosine values respectively to make the values periodic and feed them to the autoencoder model.
The values in monolayer environment are labelled 0 and the values in bilayer environment are labelled 1.

Requirements:
1. Python Installed
2. Tensorflow package
3. Numpy
