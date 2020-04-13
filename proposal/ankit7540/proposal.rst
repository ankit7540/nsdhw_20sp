-----------------------
Proposal for Confocal
-----------------------

A package for modelling light intensity profile in a confocal microscope using Huygens-Fresnel principle.

https://github.com/ankit7540/Confocal

Problem to solve
################

Confocal microscopes achieve looking at a specific plane in/of some object which can be a liquid or a living cell. This 2D plane has a finite thickness
which governs the volume observed by the microscope. In spectroscopic applications, the volume of the medium observed by the confocal
microscope is important (as in my reasearch). One simple use is to determine intrinsic property of molecules to give some signal, which can 
be determined if the concentration in a liquid and the confocal volume is known.

Field : Optics, Spectroscopy

Principle : Huygens-Fresnel principle

Algorithm : 3D integrals of complex valued functions


Perspective users
################

Researchers using confocal microscopes

System architecture
################

General idea:

 1. There are n number of identified parameters required to model a microscope and I plan to used some defaults and some user input values to set up the calculation. 

 2. Next, is the sanity check for the parameters to be valid within physical limits.
 
 3. Do computation
 
 4. Print different level of results based on earlier used input.
 
 
----------
 
Flowcharts:

Analyze how your system takes input, produces results, and performs any other operations.

Describe the system's work flow. You may consider to use a flow chart but it is not required.

Specify the constraints assume in your system. Describe how it is modularized.


API description
################

Show how a user programmatically uses your system. You are supposed to implement the system using both C++ and Python. Describe how a user writes a script in the system. If you provide API in both C++ and Python, describe both.
Engineering infrastructure

Describe how you plan to put together the build system, testing framework, and documentation. Show how you will do version control.

You may use continuous integration, but it is not required. If you use it, describe how it works in your code development.

Schedule
################

|                            | Core computation                            | Time frame       |
|----------------------------|---------------------------------------------|------------------|
| Pure python implementation | SciPy (Numpy arrays used to setup matrices) | 2-3 weeks        |
| Second version             | C++ with PyBind                             | rest of the time |
|                            |                                             |                  |





References
################

Confocal volume in laser Raman microscopy depth profiling, Yutaka Maruyama & Wataru Kanematsu, Journal of Applied Physics, 110, 103107 (2011)  (`link<https://overclocked.space/index.php/s/u0W3hv48ktj01KU>`_)

https://overclocked.space/index.php/s/u0W3hv48ktj01KU
