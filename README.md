# CaseStudy_ThermalMass

Objective of the study:
analysis of the potential of the thermal mass of residential buildings for heat demand peak shaving

Case study:
a Swedish neighborhood, located in Stockholm

Methodology:
co-simulation by means of the zerOBNL (https://github.com/IntegrCiTy/zerobnl)

Scenarios:
1) Reference scenario (S1)
2) Unconstrained thermostat (S1)
3) Constained thermostat (S3)
4) Improved walls insulation (S4)
5) Improved walls insulation - Unconstrained thermostat (S5)
6) Improved walls insulation - Constained thermostat (S6)

Instructions:
- clone/download the repository
- follow the zerOBNL installation notes provided at https://github.com/IntegrCiTy/zerobnl
- since a TRNSYS and an EnergyPlus environments are created, make sure that:
  - the python package fmipp is installed in your virtual environment (https://pypi.org/project/fmipp/)
  - you are able to launch the related co-simulation nodes locally (https://integrcity.github.io/zerobnl/docu.html) 
- for each scenario, launch the script Main.ipynb by using the Jupyter notebook (https://jupyter.org/)
- for aggregated results, each scenario folder contains a PostProcess.ipynb script
