# Outdated and archived; examples moved to the gallery. See https://empymod.github.com/emg3d-gallery.

# Examples for [emg3d](https://github.com/empymod/emg3d)


0. [Examples and Tutorials](#user-content-0-examples-and-tutorials)
1. [Comparisons](#user-content-1-comparisons)
2. [Reproducing published results](#user-content-2-reproducing-published-results)
3. [Interaction with other tools](#user-content-3-interaction-with-other-tools)
4. [Tools](#user-content-4-tools)
5. [Various](#user-content-5-various)
6. [Time-domain](#user-content-6-time-domain)


## 0. Examples and Tutorials
* [0a_Minimum_working_example](./0a_Minimum_working_example.ipynb)  
  Minimum working example to get started with `emg3d` and plotting the result.

* [0b_Parameter_tests](./0b_Parameter_tests.ipynb)  
  How to compare different settings.

* [0c_Total-vs-PS-Field](./0c_Total-vs-PS-Field.ipynb)  
  Comparison of total field versus primary-secondary field calculations.


## 1. Comparisons
* [1a_1D_VTI_empymod](./1a_1D_VTI_empymod.ipynb)  
  1D VTI comparison between `emg3d` and `empymod`.

* [1b_2D_triaxial_MARE2DEM](./1b_2D_triaxial_MARE2DEM.ipynb)  
  2D with tri-axial anisotropy comparison between `emg3d` and `MARE2DEM`.

* [1c_3D_triaxial_SimPEG](./1c_3D_triaxial_SimPEG.ipynb)  
  3D with tri-axial anisotropy comparison between `emg3d` and `SimPEG`.

* [1d_1D_VTI_empymod-Laplace](./1d_1D_VTI_empymod-Laplace.ipynb)  
  1D VTI comparison between `emg3d` and `empymod` in the Laplace domain.


## 2. Reproducing published results
* [2a_SEG-EAGE_3D-Salt-Model](./2a_SEG-EAGE_3D-Salt-Model.ipynb)  
  SEG-EAGE 3D Salt Model as presented by Mulder, 2007.

## 3. Interaction with other tools
* [3a_GemPy-discretize-emg3d](./3a_GemPy-discretize-emg3d.ipynb)  
  Calculating the CSEM response for a geological model created in GemPy.

## 4. Tools
* [4a_RAM-requirements](./4a_RAM-requirements.ipynb)  
  Calculating the required memory as a function of model size.

* [4b_Runtime](./4b_Runtime.ipynb)  
  Calculating the required runtime as a function of model size.

* [4c_Check_boundary4airwave](./4c_Check_boundary4airwave.ipynb)  
  Example how to verify if the model limits are far enough in x, y, and z.

## 5. Various
* [5a_Obtaining_the_magnetic_field](./5a_Obtaining_the_magnetic_field.ipynb)  
  Calculating the magnetic field from the electric field obtained from `emg3d`.

* [5b_Magnetic_permeability](./5b_Magnetic_permeability.ipynb)  
  Calculating a model with magnetic permeability.

* [5c_Magnetic_source_using_el_loop](./5c_Magnetic_source_using_el_loop.ipynb)  
  E and H fields from a magnetic source generated by an electric loop.

* [5d_Magnetic_source_using_duality](./5d_Magnetic_source_using_duality.ipynb)  
  E and H fields from a magnetic source using the duality principle.

## 6. Time-domain
* [6a_Fullspace](./6a_Fullspace.ipynb)  
  Transient CSEM for a homogeneous fullspace, using FFTLog or DLF..

* [6b_Marine-1D](./6b_Marine-1D.ipynb)  
  Transient CSEM for a layered, marine model.
