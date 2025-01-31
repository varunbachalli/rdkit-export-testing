## To Export more functions. 

1. fork this rdkit repo. Make whatever changes you want in the clone!
2. also either clone this repo. 
3. In `Code/MinimalLib/docker/Dockerfile` where-ever it's `rdkit-export-testing` change it to the name of your fork.
4. In `Code/MinimalLib/scripts/build_rdkitjs.sh` put the url to your fork!
5. If you want to add any functions that you want to export, then just export it in jswrapper.cpp
6. from the `Code/MinimalLib` directory run `bash scripts/build_rdkitjs.sh` in command line
7. the exported files will be under `Code/MinimalLib/Code/MinimalLib/dist/`
8. Use the exported rdkit files

