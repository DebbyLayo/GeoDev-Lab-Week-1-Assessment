# GeoDev-Lab-Week-1-Assessment
PROJECT BRIEF

Project Title: Assessing Health Facility Provision and Population Coverage in Kogi State Using GIS

**Project Overview**

This project assesses the distribution and adequacy of health facilities across the 21 Local Government Areas (LGAs) of Kogi State, Nigeria.
The study will examine the number and types of health facilities in each LGA and compare them with the population to identify areas with potential health facility deficits.

**Research Question**

Are health facilities adequately distributed to serve the population across the Local Government Areas of Kogi State?

**Why It Matters**

Adequate access to healthcare requires health facilities to be sufficient and reasonably distributed across communities.
This project will provide spatial evidence on health facility distribution and identify LGAs where the available facilities may not be sufficient for the population.

**Study Area**

Kogi State, Nigeria.

**Data Required**

- Kogi State boundary
- LGA boundaries
- Health facility locations
- Health facility types/levels
- Population data
- Recommended population-to-facility standards

**Data Sources**

1. State Boundary
**Dataset:** GRID3 NGA Operational State Boundaries  
**Source:** GRID3  
**Format:** GeoPackage  
**Use:** Select Kogi State from the national dataset.

2. LGA Boundaries
**Dataset:** GRID3 NGA Operational LGA Boundaries  
**Source:** GRID3  
**Format:** GeoPackage  
**Use:** Select the LGAs within Kogi State.

3. Health Facilities
**Dataset:** GRID3 NGA Health Facilities v3.0  
**Source:** GRID3 Data Hub  
**Format:** GeoPackage  
**Use:** Filter/clip the dataset to Kogi State.

**Dataset Link:**
https://data.grid3.org/datasets/827e3638dc204f4b9ddbbd19b00954d6/about

4. Population Data
Population data for the Local Government Areas of Kogi State will be obtained from an appropriate official or reliable source.

5. Health Facility Standards
Relevant Nigerian health-sector standards will be used to determine the recommended population coverage for different levels of healthcare.

**Methodology**
1. Obtain the Kogi State and LGA boundary data.
2. Obtain the GRID3 health facility dataset.
3. Extract health facilities located within Kogi State.
4. Classify the facilities by level/type of healthcare.
5. Count the facilities in each LGA.
6. Obtain population data for each LGA.
7. Compare the number of facilities with the population of each LGA using the relevant standards.
8. Identify LGAs with potential health facility deficits.
9. Produce maps and tables showing the results.

**Expected Output**
- Map showing health facility distribution across Kogi State.
- Number of health facilities by LGA.
- Distribution of facilities by level/type.
- Population-to-facility comparison.
- Identification of LGAs with potential health facility deficits.
- Summary tables and GIS maps.

## Tools
- QGIS
- GeoPackage
- GIS and spatial analysis techniques
