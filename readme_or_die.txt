README_OR_DIE.TXT

When cloning this repository to your machine to run examples locally,
it's necessary to have GMT and PyGMT installed in an environment first.
Users can use the requirements.txt (and environment.yml) file to set up their environment,
but it's highly recommended to seek details about GMT and PyGMT on the
website https://www.pygmt.org/latest/get_started/index.html.

Remember to activate your environment "pygmt" before to use these notebooks and install jupyter notebook. **Important note**: In my case, I use miniconda, and I needed to install "notebook" and "ipykernel" in my pygmt environment. 

Run `pip install notebook` to install Jupyter notebook, if not already installed.

Run `pip install ipykernel` to install ipykernel in this environment.

Run `python -m ipykernel install --user --name=pygmt` where pygmt is the name of the environment.

This repository is a more in-depth complement to the course material at
https://github.com/GenericMappingTools/egu22pygmt.

Feel free to modify according to your needs.
@andrebelem@id.uff.br
