# MAPPING - debiasing graph neural networks for fair node classification with limited sensitive information leakage
This is the official implementation of the 'MAPPING' paper accepted by WWW Journal.


## Running Process:

1. Download datasets from [NIFTY](https://github.com/chirag-agarwall/nifty/tree/main/dataset). Then save it into ./dataset folder.
2. Run formal_debias.ipynb. A German example is provided.  
3. For different graphs, tune corresponding hyperparameters in formal_debias.ipynb.
4. To replicate visual results, run Primary Analysis.ipynb.
5. The simplest way to replicate the debiasing performance is to load debiased graphs provided in the Debiased Graphs folder. Then use dataset_edge_index_debias and dataset_x_emb_500 to run the run_gnn function in formal_debias.ipynb. Please revise the hyperparameters accordingly (plz see the paper).

## Statement:

Unfortunately, I cannot provide all the codes (especially the baselines) I used for this research. I stored all codes in my university’s server with limited storage space. I usually downloaded and deleted files after finishing one research. But unluckily I lost my files last summer as my MacBook m1 needed to replace a chip… 
