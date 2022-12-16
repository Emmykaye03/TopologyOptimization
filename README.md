# TopologyOptimization

For CSE-620 @ University of Louisville

Problem statement: 

Create a project related to algrithms and methods used in class. Establish a connection betweeen these problems and how they relate to solving real-world challenges. 

Our project proposal: 
Structural topology optimization is a design problem in which the goal is to reduce the amount of material (cost) required to build a product while maintaining that product’s overall structural integrity (quality).  Constraints are applied to specific spaces that should always be either filled or empty according to the design’s use-case.  Forces are applied to against specified surfaces to determine whether a generated structure is compliant with minimum load requirements.  Structural integrity is determined by physics-based equations that take elastic energy, deformation, and volume into consideration.  Product design is a common, real-life problem.  Our plan is to use structural topology optimization to design a standing desk product with a standard flat desktop and two additional raised platforms for a dual-monitor setup.  A simulation-based approach could utilize existing software such as Blender (with Python scripting) or Unity (with C# scripting) while applying optimization methods learned throughout this course to optimize a simple, voxel-based tensor (aka, 3D cube-units version of a pixel-based matrix).  The number of solid voxels would indicate the amount of material used (cost) for any particular solution.  Given the necessary parameters to define a search space for compliant solutions, voxels could easily be translated into a binary-based representation (0 being empty cube space, 1 being filled cube space) to be utilized within a genetic-based algorithm to generate adequate solutions or, given small enough dimensions, brute force could even be used to find the entire set of highest quality solutions with the least material cost.

Goal: 
Create two algorithm that helps with the process of Topology Optimization and discuss results related to how CAD programs work to optimize solutions.

Result: 
We discovered the challenges related to this specific problem instance - related to structural integrity, the stiffness equation, and the complexities related to creating a standing desk versus a smaller item such as a cantilever beam. 

Technologies used: 
Jupyter notebook (python)
Solidworks (as a resource for comparision)
