# Sup
The base workflow command run is:
```
clas12-workflow.py --model "decrec" --phaseSize 1 --outDir "/volatile/clas12/benkel/data/out" --logDir "/volatile/clas12/benkel/data/log" --runGroup "rge" --tag "fmtacc$COATVERSION" --inputs "/mss/clas12/rg-f/data" --runs 12016 --coatjava "$COATVERSION" --reconYaml "/work/clas12/users/benkel/data/rge/yaml/$YAMLVERSION.yaml" --threads 16
```
Remember to add `--submit` at the end when everything looks good!
