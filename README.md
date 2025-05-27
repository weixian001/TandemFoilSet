# CFD Dataset Generation for Tandem-Airfoil Flow Prediction

This repository contains the dataset generation code for high-fidelity CFD simulations used in our flow prediction benchmarks. 
It supports a wide range of aerodynamic configurations, from single and tandem airfoils to race cars.

# CFD Dataset Generation Codes

This repository contains dataset generation pipelines for computational fluid dynamics (CFD) simulations across three different geometry families:

1. **Tandem Cruise Fixed** : 
	tandemAirfoil/autoSingle_woO_match: to generate single-airfoil datasets at AOA=0 and 5
	tandemAirfoil/tandem_cruise: to generate tandem-airfoil curise datasets at AOA=0 and 5
	tandemAirfoil/tandem_takeoff: to generate tandem-airfoil takeoff datasets at AOA=5 with ground effect
2. **Random Fields** : 
	randomFields/run_random_single: to generate single-airfoil datasets at random flow field
	randomFields/run_random_cruise: to generate tandem-airfoil datasets at random flow field
3. **Race Cars** : 
	raceCar/run_singleRaceCar: to generate inverted single-airfoil datasets with ground effect at random flow field
	raceCar/run_raceCar: to generate race car datasets with gorund effect at random flow field

Each folder includes scripts to create geometry, mesh it, and run simulations. 


## Dataset Access

- **Single-Airfoil Datasets**  
  [🔗 NTU Dataverse (Private Link)](https://researchdata.ntu.edu.sg/privateurl.xhtml?token=aa15b61a-3dcf-4e56-a46c-2bf48c8045c6)

- **Tandem-Airfoil Datasets**  
  [🔗 NTU Dataverse (Private Link)](https://researchdata.ntu.edu.sg/privateurl.xhtml?token=4c8c4bdc-f361-41b2-971f-48f6ab7e4548)
