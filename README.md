# Bayesian Similarity
Applying gaussian processes to find the optimal similarity thresholds in an embedding space 
Tested agaist mean -and linear -baseline  

To run the project: 

1. git clone 
2. uv venv
3. source .venv/bin/activate
4. uv pip sync uv.lock
5. run the files 


There is two notebooks.
1. detemine_optimal_STs_and_embs.ipynb
   it just process pre-computed embeddings and clustering files. Only parts of this script is possible to run, to avoid uploading large datasets.
2. main_analysis.ipynb
   Where all the analysis happens


Be aware that the GP cell takes appr. one hour 
