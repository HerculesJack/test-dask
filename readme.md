To set up the environment, please use:

```
conda create -n test-dask python=3.6 -c conda-forge --yes
source activate test-dask
conda install -c conda-forge numpy cython dask matplotlib multiprocess numdifftools scikit-learn scipy ipykernel --yes

git clone https://github.com/HerculesJack/bayesfast
cd bayesfast
git checkout dev
pip install -e .
```
