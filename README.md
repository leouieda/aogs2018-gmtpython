# Integrating the Generic Mapping Tools with the Scientific Python Ecosystem

[Leonardo Uieda](http://www.leouieda.com)
and
[Paul Wessel](http://www.soest.hawaii.edu/wessel/)

Poster presented at the Asia Oceania Geosciences Society
(AOGS) 2018 15th Annual Meeting at Honolulu, HI, USA.

||Info|
|---:|:---|
|Abstract ID|SE28-A065|
|Time|Thursday 2018-06-07 13:30 - 15:30|
|Room|Ballroom B|
|Download|doi:[10.6084/m9.figshare.6399944](https://doi.org/10.6084/m9.figshare.6399944)|


## Abstract

The Generic Mapping Tools (GMT) are used throughout the geosciences to
processes spatial data and create publication quality data visualizations, such
as contour maps, earthquake focal mechanism solutions, and animations. The
software is programmed in the C language and is accessed through a command-line
interface. Recent versions of GMT also provide an Application Programming
Interface (API) that allows access to the core functionality from other
programming languages, potentially expanding the reach of GMT far beyond the
current user base. A GMT toolbox for Matlab using the API has already been
released, and an experimental interface from the Julia language is being
developed. We are building a software library to interface GMT with the Python
programming language. Popularity of Python has grown steadily in the Earth
Sciences due to its simplicity and powerful set of scientific libraries.
However, there is still great need for the geospatial processing and mapping
capabilities of GMT. The GMT/Python library integrates with the scientific
Python ecosystem through the support of common Python data types: numpy
"ndarrays" and Pandas "DataFrames" for tabular data and xarray "Datasets" for
grids. We have also implemented support for the Jupyter notebooks, a web-based
interactive computing environment (an example is available at
http://try.gmtpython.xyz). These features will help make GMT more accessible to
students and professional geoscientists who lack an extensive background in
Unix tools and shell scripting. GMT/Python is an open-source project in early
stages of development. The current focus is on the implementation of a robust
set of core routines that implement the bridge between Python and GMT. Later,
we will expand the library to cover the entire functionality of GMT. A first
release is predicted for the late 2018. The latest documentation and source
code can be accessed through the website http://www.gmtpython.xyz.

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img
alt="Creative Commons License" style="border-width:0"
src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br>
This content is licensed under a <a rel="license"
href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution
4.0 International License</a>.

All source code is distributed under the [BSD 3-clause
License](https://opensource.org/licenses/BSD-3-Clause).

