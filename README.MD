## Install package
Conda create new environment
`conda create --name your_env python=3.8`
Install Jupyter notebook Kernel
`conda install -c anaconda ipykernel`
Install requirement packages of Metacomp
`pip install -r requirements.txt`
or `pip3 install -e .`
Then install jupyter-notebook kernel
`python -m ipykernel install --user --name=MetaComp`
Run jupyter notebook --> choose MetaComp kernel
`jupyter-notebook`

