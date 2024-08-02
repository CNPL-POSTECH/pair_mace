How to use:

sh patch_lammps.sh /path_to_lammps/

cd /path_to_lammps/

mkdir build

cd build

cmake ../cmake -DCMAKE_PREFIX_PATH="python -c 'import torch;print(torch.utils.cmake_prefix_path)'"

