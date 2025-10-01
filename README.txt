## Acknowledgments
This project makes use of the following repositories:
https://bitbucket.org/ahickok/vineyard/src/main/
https://github.com/zsteve/tpot.git


Starting with a file txt/tsv:

1) get_filtration notebook to extract filtration, barcodes and persistence with Gudhi, create JSON file with the information extracted.

2) get_representatives notebook to extract representative cycles and barcodes with Ripserer.JL, save it in a JSON file.


3) visualize representative cycles with vis_cycles notebook.

4) get_vines notebook to compute vineyards

5)TpOT_matching notebook to compute TpOT algorithm 


