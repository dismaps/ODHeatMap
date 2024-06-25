ODHeatMap: A Global Open Data District Heating Model (v1.1)
---
Regarding the tool:
  * The objective of the tool is to *extract building footprints to calculate building surface area, and with that estimate buildings heat demand to assess District Heating feasibility.* **All of this using open data.**
  * The model is particularly useful when lacking data availability and accesibility.
  * It is set up as a 4 step workflow and the script allows for user flexibility and adaptability of the code.
  * All temporary outputs are saved in this notebook content directory: "/content/" and all geodata files are in GeoPackage format (.gpkg)
* For more information on the tool, visit the paper [in reviewing process]
* Help us improving the tool by sending comments via email [email](<'diana@plan.aau.dk'>)
* Check out more about the [Sustainable Energy Planning and Management](https://www.en.aau.dk/education/master/urban-energy-and-environmental-planning/sustainable-energy-planning-management) group  at [AAU](https://www.en.aau.dk/)
---
* Overview of the tool's workflow:

> Step 1: Retrieving building footprints as data input for the rest of the workflow.

> Step 2: Estimating the buildings envelope as surface area input.

> Step 3: Estimating the heating demand at a building level.

> Step 4: Estimating District Heating (DH) potential at an aggregated grid level.

! [Workflow] (ODHeatMap_workflow_SKETCH3.emf)

* Software considerations:
> The tool is written in a set of steps that guide and ask the user for inputs and the outputs are saved in the notebook content directory when running the tool.
> The default geographical file format utilized in the code is GeoPackage (.gpkg) as to optimize the outputs handling compatibility of GIS and non-GIS software.
