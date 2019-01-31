# Datasets

Dataset with cubes in .ply format (in a zip file).

This is easily used from a Google Colab Python notebook.

The cubes have been generated through scripts in <https://github.com/mrquincle/octave-scripts>.

There are two datasets:

* single_cubes.zip
* cubes.zip

The first zip file contains 3D point clouds of single cubes. The second zip file contains 3D point clouds with multiple cubes, generated through a Dirichlet Process.

# Obtain files

The files can be obtained by cloning:

    !git clone https://github.com/mrquincle/dataset-cubes
    !cd dataset-cubes && git log -1
    !cd dataset-cubes && unzip -q cubes.zip

Or individually through:

    !wget https://github.com/mrquincle/dataset-cubes/raw/master/cubes.zip
    
As soon as my PhD thesis is finished, feel free to cite it if you use this dataset.
