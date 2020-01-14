Supplementary interactive notebooks for the QCS paper
=====================================================

[![Binder](https://mybinder.org/badge_logo.svg)][binder]
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3606735.svg)][zenodo]

Binder repository for the code and datasets that underpin the results in the paper
[*A quantum-classical cloud platform optimized for variational hybrid algorithms*][arxiv]
by [Peter J. Karalekas][peter], [Nikolas A. Tezak][nikt], [Eric C. Peterson][eric],
[Colm A. Ryan][colm], [Marcus P. da Silva][marcus], and [Robert S. Smith][robert].
The `notebooks` directory contains Jupyter notebooks that reproduce all of the analysis
and plotting for the paper, using the data in the `notebooks/datasets` directory. All the
resulting plots and figures are in the `figures` directory. To run the notebooks in a
preconfigured environment on Binder, click the badge above!

Alternatively, you can run the image locally with the following command (replacing `PORT`
with the `localhost` port you'd like to run the notebook server on):

```bash
docker run -p PORT:8888 rigetti/qcs-paper
```

This will start the container, and somewhere in the terminal output it will print a URL that
looks something like the following, but with `TOKEN` replaced with a long string of letters
and numbers:

```
http://127.0.0.1:8888/?token=TOKEN
```

Copy paste the above URL into your browser, replacing 8888 with `PORT`. This will bring up the
JupyterLab interface.

## Paper Citation

```bibtex
@misc{karalekas2020quantumclassical,
    title={A quantum-classical cloud platform optimized for variational hybrid algorithms},
    author={Peter J. Karalekas and Nikolas A. Tezak and Eric C. Peterson and Colm A. Ryan and Marcus P. da Silva and Robert S. Smith},
    year={2020},
    eprint={2001.04449},
    archivePrefix={arXiv},
    primaryClass={quant-ph}
}
```

[arxiv]: https://arxiv.org/abs/2001.04449
[binder]: https://mybinder.org/v2/gh/rigetti/qcs-paper/master?urlpath=lab/tree/Welcome.ipynb
[colm]: https://github.com/caryan
[eric]: https://github.com/ecpeterson
[marcus]: https://github.com/marcusps
[nikt]: https://github.com/ntezak
[peter]: https://github.com/karalekas
[robert]: https://github.com/stylewarning
[zenodo]: https://doi.org/10.5281/zenodo.3606735
