MeshSimplification
---------------------
The simpilification results of our method with different cofficients of k_sv and k_sd are provided in '0.3ksv_0.7ksd_0.2ksq' and '0.4ksv_0.6ksd_0.2ksq' folder respectively, the simplification results of ranking by valence term and width term are also provided in 'valence_term' and 'width_term' folder respectively. Moreover, the mesh file (.vtk), histogram of scaled Jacobian (.png) and statistics (.txt) are included in each folder. The statistics of results includes minimum scaled Jacobian, average scaled Jacobian, Hausdorff distance ratio, the number of base-complex components, and total time.
----------------------
**Usage**: On Windows, the executable files (.exe) of corresponding parameters are included in each folder. 
	The .exe file can run by the command that 'complex_simplification.exe SIM R B SR F input', in which R is the ratio of
	the simplification of mesh elements, B is the base number for optimization iteration, SR is the ratio of target
	simplification ratio of base-complex components, F is 0 means that input mesh include sharp feature, and input is the
	name of input mesh file (.vtk).
	An example of default command: complex_simplification.exe SIM 1 2 1 0 ./octree/airplane1_input_tri_hexa