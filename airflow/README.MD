# System requirements #
The system requirements for running this Python code are:

- Python 3.x installed on the system
- csv and os libraries installed
- rdflib library installed 

# Installation requirements #

```
pip install apache-airflow
pip install rdflib
```
# Folder description # 
## dags ##
Contents python scripts:
- data-cubes.py for creating DAG in Apach AirFlow
- care_providers.py and population.py from previous HW (script description you can find in folder hw1)
## input ##
Folder is generated automatically by Python when you run a script if the folder has not already been created. 

Contents csv files:
- care_providers.csv
- country_codelist.csv
- population.csv

## output ##
Folder is generated automatically by Python when you run a script if the folder has not already been created. 

Contents ttl files:
- health_care.ttl
- population.ttl

# File Description #

## data-cubes.py ##

### Run ###
```
python data-cubes.py
```
### Input ### 
- have files named population.py and care_providers.py located in the same folder as the script data-cubes.py

### Output ###
- health_care.ttl
- population.ttl
