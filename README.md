### ODYM-RECC Copper
Python code of the ODYM-RECC Copper model (https://doi.org/10.1016/j.resconrec.2023.106941)

Resources Conservation and Recycling 

### Sector-level estimates for global future copper demand and the potential for resource efficiency

Stefanie Klose1* and Stefan Pauliuk1

1 Faculty of Environment and Natural Resources, University of Freiburg, Germany
To whom correspondence should be addressed: *) Stefanie Klose, stefanie.klose@posteo.de; 

Guide to the ODYM-RECC Copper model
This paper comes with a supplementary file, the code achieve on github, and supplementary files on ZENODO: https://doi.org/10.5281/zenodo.7249829
To run the model, one 

1) needs to extract the data folder from ZENODO and copy its content to a convenient location. 
2) save the following excel files RECC-Classifications_Master_V2.0 and RECC_Config from this github repository in the same folder as your data.
3) save the python scripts from this repo in a convenient location
4) Enter the respective paths in the RECC_Paths.py file
5) Specify in the RECC_Config file which Sectors (l. 198) you want to model. Specify the goods (l. 29) and Manufacturing processes (l. 27) accordingly. The Config_Sandbox sheet in the RECC_Config file gives you the numbers of the goods in the different sectors as specified in the RECC_Classifications_Master_V2.0
