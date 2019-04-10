# NLTK Demo #
Created by Aki Ariga (aki@cloudera.com)  
This demonstrates how to distribute libraries out the worker nodes without having them pre-installed on the nodes. In this instance, we'll distribute the NLTK library. 

## Status: ## 
Demo Ready  
## Use Case: ##
Library Distribution

## Steps: ##
1. In your projects, go to Settings > Engine and set the following environment variables:  
`SPARK_CONFIG=NLTK-demo/spark-defaults.conf` --	(defaults for distribution)  
`PYSPARK_PYTHON=/anaconda/bin/python2.7` --	(local python)
2. Open a terminal, cd to NLTK-demo and run setup.sh  
3. Create a Python Session and run pyspark_nltk.py  

## Recommended Session Sizes: ## 
2 CPU, 4 GB RAM

## Estimated Runtime: ##  
pyspark_ntlk.py --> < 15 seconds 

## Recommended Jobs/Pipeline: ##  
None

## Demo Script ## . 
TBD

## Related Content: ##  
https://wiki.cloudera.com/display/~ariga/2017/04/11/How+to+Run+your+favorite+Python+library+On+PySpark+cluster+without+IT+permission+on+CDSW

