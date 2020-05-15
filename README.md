# Flight Performance Analysis for an RV-8 Aircraft

This is a Jupyter Notebook-based performance analysis of an RV-8 aircraft, used for an end-of-semester talk.

![Thrust Required Plot](https://raw.githubusercontent.com/bws428/flight-performance-analysis/master/charts/thrust-required-0.png)

## Anaconda Python

These instructions presume the user has installed the [Anaconda](https://www.anaconda.com/) Python distribution, and is using the `conda` package manager.  The Anaconda Individual Edition is free and open source.

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

Fire up the notebook:

```bash
jupyter notebook
```

To deactivate an active environment, use

```bash
conda deactivate
```
