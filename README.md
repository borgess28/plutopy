# plutopy
Welcome to **plutopy**! This is a learning library for scientists new to Python, Git, GitHub or all three. 

## Overview
This repository exists to import, visualize and manipulate an image of Pluto taken by the New Horizons mission in 2015.

## Example
TODO: Take some screenshots of plutopy in action and add them to the README.

## Tutorial
TODO: Create a full worked example of plutopy in action in a Jupyter notebook, and add a link to the README. 

## Data
The image used is the *Pluto New Horizons Global Mosaic 300m July 2017*. The data was collected by [Moore et al. 2016](https://arxiv.org/abs/1604.05702) and made vailable by the U.S. Geologic Survey [here](https://astrogeology.usgs.gov/search/map/Pluto/NewHorizons/Pluto_NewHorizons_Global_Mosaic_300m_Jul2017).

The features of interest are stored in the Comma Separated Values (CSV) file format.

## Processing
The image handling is done with Python bindings for [GDAL](https://www.gdal.org/index.html), features of interest are read in with [Pandas](https://pandas.pydata.org/pandas-docs/stable/), the analysis is done with [numpy](http://www.numpy.org/) and [scipy](https://www.scipy.org/about.html), and the plotting is done with [matplotlib](https://matplotlib.org/). The tutorial is written in a Jupyter notebook. 

Some useful tutorials/documentation on the above packages:
- [Python GDAL/OGR Cookbook](https://pcjericks.github.io/py-gdalogr-cookbook/)
- [10 Minutes to pandas](https://pandas.pydata.org/pandas-docs/stable/10min.html)
- [Numpy Quickstart tutorial](https://docs.scipy.org/doc/numpy-1.15.0/user/quickstart.html)
- [Scipy Tutorials](https://docs.scipy.org/doc/scipy/reference/tutorial/index.html)
- [Matplotlib.pyplot Tutorial](https://matplotlib.org/users/pyplot_tutorial.html)

## Contributing
All contributors to this project are listed in [CONTRIBUTORS.md](./CONTRIBUTORS.md). If you would like to be a contributor, first read [CONTRIBUTING.md](./CONTRIBUTING.md) and then head over to the [issue tracker](https://github.com/cjtu/plutopy/issues) and start with issue #1. All are welcome!

### Code of Conduct
This repository is governed by a code of coduct. See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) for more details.

## License
This repository is released under the MIT license for open and warranty-free use and reproduction. See the [LICENSE](./LICENSE) for more details. To learn more about the imporance of a license or what different licenses mean, [Choose a License](https://choosealicense.com/no-permission/) is a great resource.


