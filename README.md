## Acknowledgments
This project makes use of the following repositories:  
- [Vineyard](https://bitbucket.org/ahickok/vineyard/src/main/)  
- [TpOT](https://github.com/zsteve/tpot.git)  

---

## Workflow

Starting with a `.txt` or `.tsv` file, the analysis proceeds as follows:

1. **get_filtration** notebook  
   Extracts filtration, barcodes, and persistence using Gudhi, and creates a JSON file with the extracted information.

2. **get_representatives** notebook  
   Extracts representative cycles and barcodes using Ripserer.JL, saving the results in a JSON file.

3. **vis_cycles** notebook  
   Visualizes the representative cycles.

4. **get_vines** notebook  
   Computes the vineyards.

5. **TpOT_matching** notebook  
   Computes the TpOT algorithm.
