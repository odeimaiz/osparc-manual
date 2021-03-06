# Services

Every study in o<sup>2</sup>S<sup>2</sup>PARC is composed of at least one so-called service, though most studies will contain multiple services.

Services can provide data/files, visualize results (2D, 3D), implement code in [Jupyter notebooks](https://jupyter.org/) or perform computations to execute simulations within a study.

The computational backend involves all services needed to handle the actual computational workload. A computational workflow is described as a pipeline that processes a stream of data in a sequential way. Every pipeline consists of multiple algorithms, each one expecting specific input data and providing specific output data.

The pipeline can be built up as a directed acyclic graph (dag) where the lines between the services describe input/output flows and the nodes represent the algorithms (i.e., the computational kernels). Such kernels include standalone solvers, algorithms to perform specific calculations, or viewers that render data into graphs, plots or tables, etc.

All these services can be already provided within a study template or can be set up from scratch by the user by selecting options in the service catalog.

<img width="1018" alt="Screenshot 2019-07-21 at 16 46 02" src="https://user-images.githubusercontent.com/32800795/61592697-14651d00-abd7-11e9-9319-a1ee9548803e.png"> <br/>
*Connected services as well as selection of services via the service catalot in the workbench.*