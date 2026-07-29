# embed_pdbs
Here I will make the pdbs that I want to embed in my notion pages publicly available for molstar
### How to embed any pdb in notion

1. Include an embed block
2. Paste a molstart link
    1. If the protein is in the pdb database, use the following URL
        
        ```
        https://molstar.org/viewer/?pdb={id}
        
        # To load more than one
        https://molstar.org/viewer/?pdb={id},{id}
        
        # To load from AF db
        https://molstar.org/viewer/?afdb={id}
        ```
        
    2. If the protein is your own pdb file, upload it to the embed_proteins github repo and use the following URL
        
        ```
        https://molstar.org/viewer/?structure-url={raw_url}&structure-url-format=pdb

        # IMPORTANT! Adapt the file format to pdb, mmcif ...
        
        # You can copy a file's raw URL from github and it will look something like
        https://raw.githubusercontent.com/eduam-lu/embed_pdbs/refs/heads/main/insulin_project/chai_IR_dimer_pred.rank_0.cif
        ```
