# Learning to Manipulate under Limited Information

README.md for the code used in the paper "Learning to Manipulate under Limited Information" by Wesley H. Holliday, Alexander Kristoffersen, and Eric Pacuit, forthcoming in the Proceedings of AAAI 2025.


## Notebooks

* Learning to Manipulate.ipynb: This is the main notebook containing all the code for training and evaluating MLPs (including code to create graphs).

* Learning to Manipulate - Graphs for Paper.ipynb: The code to produce the graphs in Figure 1 and the Supplementary Figures.

* Learning to Manipulate - Example Manipulations.ipynb: In this notebook, you can select a trained MLP (for Borda) to manipulate using majority matrix information. 

* Learning to Manipulate - Significance Testing.ipynb: In this notebook, you can find the statistical significance of the differences in profitability of manipulation between two trained MLPs. 

* model_functions.ipynb: The notebook containing all the code needed to run the code in Learning to Manipulate - Example Manipulations.ipynb and Learning to Manipulate - Significance Testing.ipynb.

* Ideal Manipulators.ipynb: Code to generate the ideal manipulator graphs in Figure 1 and the Supplementary Figures.

* supplementar-figures.pdf: The PDF containing the Supplementary Figures.

## Other Files/Directories

1. example_trained_models/Borda_1_6_10_uniform_('majority',)_1_08-18-2023_09-10-18.pickle:  Pickle file containing a dictionary of all the trained MLPs for Borda, generation 1, 6 candidates, 10 voters using majority matrix information. 

2. ideal_manipulator_data/*: Subfolders that contain the evaluation data for the ideal manipulators.

3. evaluation_csv/*: Subfolders that contain the evaluation data used for the graphs in the paper.

4. evaluation/*: Subfolders that contain the evaluation data to produce the graphs in the paper and the supplementary material. 

**Note**: Running the main notebook will generate additional subdirectories.

## Requirements

The following packages are required to run the notebooks:

- [PyTorch](https://pytorch.org/)
- [pref_voting: Preferential Voting Tools](https://pref-voting.readthedocs.io/en/latest/)
- [Google Cloud Storage](https://cloud.google.com/python/docs/reference/storage/latest)
- The notebooks and the pref_voting library is built around a full SciPy stack: [MatPlotLib](https://matplotlib.org/), [Numpy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), [numba](http://numba.pydata.org/), 
- [tqdm.notebook](https://github.com/tqdm/tqdm)
- [seaborn](https://seaborn.pydata.org/)  
- [multiprocess](https://pypi.org/project/multiprocess/) 
