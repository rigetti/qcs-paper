Supplementary interactive notebooks for the QCS paper
=====================================================

Binder repository for the code and datasets that underpin the results in the paper
*A quantum-classical cloud platform optimized for variational hybrid algorithms*
by Peter J. Karalekas, Nikolas A. Tezak, Eric C. Peterson, Colm A. Ryan, Marcus P. da Silva,
and Robert S. Smith. The `notebooks` directory contains Jupyter notebooks that reproduce
all of the analysis and plotting for the paper, using the data in the `notebooks/datasets`
directory. All the resulting plots and `figures` are in the figures directory. To run the
notebooks in a preconfigured environment on Binder, click the badge above!


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
