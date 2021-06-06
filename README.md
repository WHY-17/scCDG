# scCDG
# Single-cell clustering based on DAE and GCN.


    In this paper, we have proposed  a single cell analysis tool sccdg: single-cell clustering based on denoising autoencoder and graph convolution network. In scCDG, raw data is denoised by DAE whose lower dimensional representation is used to construct KNN graph. GCN is employed to extract main information of graph, and the low dimensional embedding is used for clustering, dimension reduction and visualization. 
    Sccdg is implemented in Python environment. If you want to run it, please install the relevant dependency packages in requirements first. It should be noted that the DAE and the graph auto encoder run independently, and the output of the former should be saved locally as the input of the latter.
    You just need to run run_DAE.py and run_scCDG.py in the folder code in order to get the results in the article. If you have any questions, please contact me. 
email: haiyun_wang_xju@163.com
