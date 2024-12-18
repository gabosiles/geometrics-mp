# geometrics-mp
CodingTools to convert stl to blend files, calculate primitive geometric figures and creating xml Mujoco based files.

#STL to BLEND module

To create the approximation of the stl model we first need to import it into blender, delete the default elements, rename the file save it and by then run the code for the calculation of the best figure.

Now to with this code it automatically imports the .stl and convert it to a.blend file so you only apply the calculationc_code.

To run it you only need to run the following command line:

blender --background --python stl_to_blend.py

Requirements stl directory and blend directory must exist in ./ so the code works, the file path is always the same
