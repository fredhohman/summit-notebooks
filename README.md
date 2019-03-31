# Summit Notebooks

```
NOTE: this project has not been announced yet, but will be at a later date. Please check back soon!
```

*Summit: Scaling Deep Learning Interpretability by Visualizing Activation and Attribution Summarizations*

Summit is a an interactive system that summarizes and visualizes what features a deep learning model has learned and how those features interact to make predictions.
This repository contains the python notebooks used to generate the data used in the [Summit visualization][summit].

For the Summit visualization, go to [https://github.com/fredhohman/summit][summit].

### Main notebooks:

* [`activation-matrices.ipynb`](activation-matrices.ipynb): generate aggregated activation matrices
* [`influence.py`](activation-matrices.ipynb): generate aggregated influence matrices
* [`activation-matrices-to-json.ipynb`](activation-matrices-to-json.ipynb): combine activation matrices per class into json format
* [`attribution-graph.ipynb`](dag.ipynb): generating class attribution graphs
* [`feature-vis-sprite-to-images.ipynb`](feature-vis-sprite-to-images.ipynb): split feature visualization sprites to single images

### Experimental notebooks:

* [`top-channels-used-per-layer.ipynb`](top-channels-used-per-layer.ipynb): analysis for determining which channels were used the most by all classes for all layers

***

## Live Demo

For a live demo, visit: [fredhohman.com/summit][demo]


## Installation

Download or clone this repository:

```bash
git clone https://github.com/fredhohman/summit-notebooks.git
```


## Usage

To run Summit Nooteboks, run a Jupyter server:

```bash
jupyter lab
```


## Resources

We used the following ImageNet metadata:

* [https://github.com/google/inception/blob/master/synsets.txt](https://github.com/google/inception/blob/master/synsets.txt)
* [https://gist.github.com/aaronpolhamus/964a4411c0906315deb9f4a3723aac57](https://gist.github.com/aaronpolhamus/964a4411c0906315deb9f4a3723aac57)
* [https://gist.github.com/yrevar/942d3a0ac09ec9e5eb3a](https://gist.github.com/yrevar/942d3a0ac09ec9e5eb3a)


## License

MIT License. See [`LICENSE.md`](LICENSE.md).


## Contact

For questions or support [open an issue][issues] or contact [Fred Hohman][fred].

[summit]: https://github.com/fredhohman/summit
[fred]: https://fredhohman.com
[demo]: https://fredhohman.com/summit/
[issues]: https://github.com/fredhohman/summit-notebooks/issues
