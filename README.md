
# Regularization strategies for Seis2Rock-based petrophysical inversion of pre-stack seismic data

> Corrales M.<sup>1</sup>, Romero J.<sup>1</sup>, Luiken N.<sup>1</sup>, Hoteit H.<sup>1</sup>, Ravasi M.<sup>1</sup>\
> <sup>1</sup> King Abdullah University of Science and Technology (KAUST)\
> https://doi.org/10.1190/image2024-4093717.1


## Project structure
This repository is organized as follows:

* :open_file_folder: **assets**: images and figures of the project.
* :open_file_folder: **seis2rock**: python library containing routines for seis2rock.
* :open_file_folder: **data**: folder containing data (and instructions on how to retrieve the data).
* :open_file_folder: **notebooks**: set of jupyter notebooks reproducing the experiments in the paper (see below for more details).


## Notebooks for Volve dataset
The following notebooks are provided:

- :orange_book: ``01_Regularization_Comparison_Well_NO_15_9_19_BT2_stacking_wells.ipynb``: Regularization comparison for fence along well NO_15_9_19_BT2.
- :orange_book: ``02_Regularization_Comparison_Well_NO_15_9_19_A_stacking_wells.ipynb``: Regularization comparison for fence along well NO_15_9_19_A. 


## Getting started :space_invader: :robot:
To ensure reproducibility of the results, we suggest using the `environment.yml` file when creating an environment.

Simply run:
```
./install_env_gpu.sh
```
It will take some time, if at the end you see the word `Done!` on your terminal you are ready to go. Αctivate the environment by typing:
```
conda activate rseis2rock_gpu
```

After that you can simply install your package: (double check your new environment is active to proceed as follows)
```
pip install .
```
or in developer mode:
```
pip install -e .
```


> **Note** <br>
> For computer time, this research used the resources of the Supercomputing Laboratory at KAUST in Thuwal, Saudi Arabia. All experiments have been carried on > a Intel(R) Xeon(R) Platinum 8260 CPU @ 2.40GHz equipped with a single NVIDIA TESLA V100. Different environment configurations may be required for different > combinations of workstation and GPU


## Cite us

```
@incollection{corrales_regularization_2024,
	series = {{SEG} {Technical} {Program} {Expanded} {Abstracts}},
	title = {Regularization strategies for {Seis2Rock}-based petrophysical inversion of prestack seismic data},
	url = {https://library.seg.org/doi/10.1190/image2024-4093717.1},
	urldate = {2024-12-18},
	booktitle = {Fourth {International} {Meeting} for {Applied} {Geoscience} \& {Energy}},
	publisher = {Society of Exploration Geophysicists and American Association of Petroleum Geologists},
	author = {Corrales, Miguel and Romero, Juan and Luiken, Nick and Hoteit, Hussein and Ravasi, Matteo},
	month = dec,
	year = {2024},
	doi = {10.1190/image2024-4093717.1},
	keywords = {inversion, machine learning, prestack},
	pages = {26--30},
}
```
