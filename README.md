# pedestrian_crossing_research_data

This repository contains pedestrian flow simulation results, which are used in article "Using Multi-Agent Simulation to Predict Natural Crossing Points for Pedestrians and Choose Locations for Mid-Block Crosswalks"

## Repository Contents

### Result Sets
This repository contains sources and results for AntRoadPlanner simulation (https://antroadplanner.ru). 2 locations were modelled in Saint-Petersburg city, and each location was modelled twice: with and without proposed crosswalks. In provided data, all files and folders are named based on their location and simulation type, e.g. "first location without crosswalks".

### File types
Repository contains following file types for any of 4 simulations:

* *case name*.json - it is a map file for AntRoadPlanner simulation engine. It may be loaded into https://antroaplanner.ru to run pedestrian flow analysis for that location.
* *case name*.sql - Dump of PostgreSQL + PostGIS database with simulation results. It contains tables with map objects locations as well as navigation graph points with pedestrian flow counts, as described in the article
* output*case name*  folders contain extra simulation output - images of intermediate simulation step results and some extra stats and data, produced by AntRoadPlanner algorithm



