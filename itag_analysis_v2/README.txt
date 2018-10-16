
## calculate shannon index and rarefraction curve
source activate my-r-env
macqiime
alpha_rarefaction.py -i Salt_pond_16S_otu.tax.filtered.biom -m ../map.txt -o arare -p alpha_params.txt -t Salt_pond_16S_otu.tax.filtered.fasttree.tree
