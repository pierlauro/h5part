Fork of [H5Part](https://github.com/glennklockwood/h5part).

Adapted for [PyVOL](https://github.com/pierlauro/pyvol).


Website:

http://vis.lbl.gov/Research/AcceleratorSAPP/

Particle based simulations of accelerator beam-lines, especially in six
dimensional phase space, generate vast amounts of data. Even though a subset of
statistical information regarding phase space or analysis needs to be preserved,
reading and writing such enormous restart files on massively parallel
supercomputing systems remains challenging.

H5Part is a very simple data storage schema and provides an API that simplifies
the reading/writing of the data to the HDF5 file format. An important
foundation for a stable visualization and data analysis environment is a stable
and portable file storage format and its associated APIs. The presence of a
"common file storage format," including associated APIs, will help foster a
fundamental level of interoperability across the project's software
infrastructure. It will also help ensure that key data analysis capabilities
are present during the earliest phases of the software development effort.

H5Part is built on top of the HDF5 (Hierarchical Data Format). HDF5 offers a
self-describing machine-independent binary file format that supports scalable
parallel I/O performance for MPI codes on a variety of supercomputing systems,
and works equally well on laptop computers. The API is available for C, C++, and
Fortran codes. The H5Part file format and APIs enable disparate research groups
with different simulation implementations to transparently share datasets and
data analysis tools. For instance, the common file format will enable groups
that depend on completely different simulation implementations to share data
analysis tools. 

