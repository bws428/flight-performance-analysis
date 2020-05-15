# Flight Performance Analysis for an RV-8 Aircraft

This is a Jupyter Notebook-based performance analysis of an RV-8 aircraft; used for an end-of-semester talk.

The notebook can be [viewed as a complete web page](http://nbviewer.jupyter.org/github/briandwendt/Flight-Performance-Analysis/blob/master/RV-8F%20Performance.ipynb) with nbviewer.

## Installation

Clone the repo:

```bash
git clone https://github.com/bws428/flight-performance-analysis.git rv-8
```

Change into the newly-created `rv-8` directory:

```bash
cd rv-8
```

Update conda:

```bash
conda update -n base -c defaults conda
```

Create the `rv-8` conda environment with required dependencies:

```bash
conda env create -f environment.yml
```

To activate this environment, use

```bash
conda activate rv-8
```

```
pip install ambiance
```

```bash
jupyter notebook
```

To deactivate an active environment, use

```bash
conda deactivate
```
