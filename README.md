# cmake_perplex
A cmake project to create a shared perplex (meemum) library for C++

To make the C header, compile all the PerpleX executables, create the shared C++ library and install to a given directory, type in the following commands:

`tar xvf cmake.tar`<br>
`cd include`<br>
`python ./create_c_header.py`<br>
`cd ..`<br>
`cmake -D CMAKE_INSTALL_PREFIX=install .`<br>
`make -fMakefile install`<br>

"install" can be changed to any preferred directory.
