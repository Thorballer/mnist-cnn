# MNIST CNN — early learning experiments

Early TensorFlow digit-classification notebooks, including a tf.data input pipeline and a subclassed CNN block.

## Project status

Historical notebooks from Daniel Goldberg’s Kaggle account, organized for a maker portfolio. The model code is preserved, not rewritten during packaging. See [PROVENANCE.json](PROVENANCE.json) for original notebook URLs, timestamps, and SHA-256 hashes.

## Notebooks

- [notebook1002c7fcf8.ipynb](notebooks/notebook1002c7fcf8.ipynb) — [original Kaggle notebook](https://www.kaggle.com/code/thorballer/notebook1002c7fcf8)
- [tutorial-8-subclassing.ipynb](notebooks/tutorial-8-subclassing.ipynb) — [original Kaggle notebook](https://www.kaggle.com/code/thorballer/tutorial-8-subclassing)

## Running

Use the original Kaggle environment where possible: open the source notebook, attach its declared datasets/models, select the hardware expected by its setup cells, and run cells in order. Inspect any install, account-login, upload, or filesystem-changing cells before executing them.

For a local adaptation, install the packages listed in `requirements.txt` in an isolated environment and adjust `/kaggle/input` paths. Those packages are inferred from imports, **not** a tested lockfile. Historical APIs and accelerator assumptions can require changes. Do not run all training notebooks at once.

## Results and limitations

The subclassing notebook is explicitly a tutorial exercise. These are early learning artifacts, not a novel architecture. Both notebooks assume an available GPU in their setup cells.

The recovered Kaggle source exports contain no retained executed outputs; this repository therefore does not advertise a numeric result based on notebook titles or training settings. Training was not rerun as part of organization. Structural validation is not a runtime or scientific validation.

## Attribution and rights

Original notebook attribution, comments, and tutorial links are preserved. Standard TensorFlow/Keras examples and tutorial-style code should not be represented as newly invented algorithms. The precise human/AI/tool contribution history is not reconstructed by this archive. No blanket new license is assigned to third-party material. Datasets, pretrained models, and tutorial-derived content retain their own licenses and access requirements; their bytes are not bundled here.
