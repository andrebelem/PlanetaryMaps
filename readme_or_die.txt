# README_OR_DIE.TXT

## Setting Up to Run Examples Locally

To run the examples in this repository on your machine, you need to have both GMT and PyGMT installed in a dedicated environment. You can use the provided `requirements.txt` or `environment.yml` file to set up the environment. However, we strongly recommend visiting the official PyGMT documentation for detailed installation instructions: [Getting Started with PyGMT](https://www.pygmt.org/latest/get_started/index.html).

## Environment Activation and Jupyter Setup

Once your environment (e.g., `pygmt`) is set up, remember to activate it before running these notebooks. Additionally, ensure that Jupyter Notebook is installed in this environment.

If you are using Miniforge (as in my setup), it may be necessary to install "notebook" and "ipykernel" manually within the `pygmt` environment.

To install these, use the following commands:

pip install notebook        # Install Jupyter Notebook
pip install ipykernel       # Install ipykernel in this environment

Then, register the kernel with:

python -m ipykernel install --user --name=pygmt


About This Repository
This repository serves as an in-depth supplement to the course material available at: EGU22 PyGMT Course Material.

Feel free to adapt any of the content here to better fit your needs.

For questions, please contact: andrebelem@id.uff.br