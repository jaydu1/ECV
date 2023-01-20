# OOBCV
Out-of-bag cross validation with risk extrapolation


## Scripts

- Section 5.1
	- `run_iso.py`
	- `run_iso_risk.py`
- Section 5.2
	- `run_iso_cv.py`
- Section 5.3
	- `run_ar1_cv_tree.py`
- Section 6
	- `convert_data.R` converts `pbmc_multimodal.h5seurat` obtained from [Seurat](https://satijalab.org/seurat/articles/multimodal_reference_mapping.html) to `pbmc_count.h5`.
	- `df_split.csv` splits training and test sets.
	- `run_real_data.py`

- Functions for runing the experiments: `compute_risk.py`, `fixed_point_sol.py`, `generate_data.py`.

- Figures: `Visualization.ipynb`