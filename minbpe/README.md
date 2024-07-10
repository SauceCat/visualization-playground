# minbpe visualization

<img src="data/minbpe.gif">

I've created a D3.js visualization to showcase the vocabulary and merges trained by the BPE algorithm. The implementation is based on Andrej Karpathy's [minbpe tutorial](https://github.com/karpathy/minbpe).

## Reproduce the data files

To reproduce the two data files needed for this visualization, follow these steps:

- Clone the minbpe repository locally.
- Copy the `minbpe_taylorswift.ipynb` file into the repository folder.
- Run the notebook.
- Finally you will get these two data files:
    - `taylorswift_minbpe_vocab.json`
    - `taylorswift_minbpe_vocab_merges.json`

## Browse the Visualization
To view the visualization, follow these steps:

- Navigate to the `minbpe` folder.
- Launch a simple Python HTTP server by running:

```bash
python -m http.server 8000
```

Open your web browser and go to http://localhost:8000/minbpe_tree.html.