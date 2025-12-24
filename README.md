# Area-Scaling-of-Dynamical-Degrees-of-Freedom

Jupyter notebook to reproduce the figures and numerical results of the paper “Area-Scaling of Dynamical Degrees of Freedom.”

This repository accompanies the manuscript and provides the numerical experiments, data handling, and plotting routines used in the paper.
(Please add the arXiv/DOI link once available.)

------------------------
## Repository contents

`area_scaling_num_expt.ipynb`
Main Jupyter notebook that runs the numerical experiments and generates all figures
appearing in the paper.

`data/`
Directory for input data and cached outputs used by the notebook.

**Note:**
The file `phi4_snapshots.npz` is not included in the repository due to its large file size.
To reproduce the corresponding figures, please run the relevant cell(s) in area_scaling_num_expt.ipynb, which generate this data automatically and save it locally in the data/ directory.

`figures/`
Output directory containing the generated figures (PDF format), matching those shown in the manuscript.

------------------------
## Usage

Open area_scaling_num_expt.ipynb.

Run the notebook cells sequentially.

If a figure depends on `phi4_snapshots.npz`, the notebook will regenerate the data when the appropriate cell is executed.

Figures are saved automatically to the figures/ directory.

------------------------
## Requirements

The notebook is written in Python and relies on standard scientific libraries (e.g. NumPy, SciPy, Numba, Matplotlib).
All dependencies are listed and imported directly in the notebook.

------------------------
## Citation

If you use this code, please cite the accompanying paper:

Area-Scaling of Dynamical Degrees of Freedom,
Varun Kushwaha et al.
(arXiv / journal reference to be added)


