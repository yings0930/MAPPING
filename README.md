# MAPPING - debiasing graph neural networks for fair node classification with limited sensitive information leakage
This is the official implementation of the 'MAPPING' paper accepted by WWW Journal.


## Running Process:

1. Download datasets from [NIFTY](https://github.com/chirag-agarwall/nifty/tree/main/dataset). Then save it into ./dataset folder.
2. Run formal_debias.ipynb. A German example is provided.  
3. For different graphs and GNN backbones, tune corresponding hyperparameters in formal_debias.ipynb, e.g., args.gnn = 'GCN'. The codes of GNN backbones are adapted from [NIFTY](https://github.com/chirag-agarwall/nifty/tree/main/dataset).
4. To replicate visual results, run Primary Analysis.ipynb.
5. The simplest way to replicate the debiasing performance is to load debiased graphs provided in the Debiased Graphs folder. Then use dataset_edge_index_debias and dataset_x_emb_500 to run the run_gnn function in formal_debias.ipynb. Please revise the hyperparameters accordingly (plz see the paper).

## Statement:

Unfortunately, I cannot provide all the codes (especially the baselines) I used for this research. I stored all codes in my university’s server with limited storage space. I usually downloaded and deleted files after finishing one research. But unluckily I lost my files last summer as my MacBook m1 needed to replace a chip… I can only find these files on the server, but they should be sufficient to run the work smoothly.

## Citation:
If you think this paper may be useful for your research, please consider citing it as:

Song, Y., Palanisamy, B. MAPPING: debiasing graph neural networks for fair node classification with limited sensitive information leakage. World Wide Web 27, 74 (2024). https://doi.org/10.1007/s11280-024-01312-0
