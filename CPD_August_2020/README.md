# Jupyter Notebooks to merge existing data on CPD officers

## Four different input files from the following sources

1. OpenOversight Production data on August 18, 2020. Download via https://openoversight.com/download/all
   1. Chicago_Police_Department_Officers.csv
   1. Chicago_Police_Department_Assignments.csv
1. From Invisible Institute
   1. 14532-P540798-InvisibleInstitute_DataInfoforallswornCPDofficers-UPDATEv2
1. Existing data work from Invisible Institute from 
   https://github.com/invinst/chicago-police-data/tree/ecb33c923a8354bd89c0273cfce78b0d6c962288/data/unified_data/profiles
   1. final-profiles.csv
   
## Requirements
1. Python 3.6+
1. [jupyter](https://jupyter.org/install.html)
1. Requirements from `requirements.txt` installed

## Layout 
Running the notebook starting with 1_ will take the input files and generate the files 1_out_xxx.
Running 2_ will take the 1_out_xxx files as input and generate the files 2_out_xxx and so on.
The files 4_out_xxx are the files ready for import on the OpenOversight server.
