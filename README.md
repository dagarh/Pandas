# PANDAS (Python for Data Analysis) #

pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible open source data analysis / manipulation tool available in any language. It is already well on its way toward this goal.

pandas is well suited for many different kinds of data:

  * Tabular data with heterogeneously-typed columns, as in an SQL table or Excel spreadsheet. </br>
  * Ordered and unordered (not necessarily fixed-frequency) time series data. </br>
  * Arbitrary matrix data (homogeneously typed or heterogeneous) with row and column labels. </br>
  * Any other form of observational / statistical data sets. The data actually need not be labeled at all to be placed into       a pandas data structure. </br>

The two primary data structures of pandas, **Series (1-dimensional)** and **DataFrame (2-dimensional)**, handle the vast majority of typical use cases in finance, statistics, social science, and many areas of engineering. For R users, DataFrame provides everything that R’s data.frame provides and much more. pandas is built on top of NumPy and is intended to integrate well within a scientific computing environment with many other 3rd party libraries.

Here are just a few of the things that pandas does well:

  * Easy handling of **missing data** (represented as NaN) in floating point as well as non-floating point data. </br>
  * Size mutability: columns can be **inserted and deleted** from DataFrame and higher dimensional objects. </br>   
  * Automatic and explicit **data alignment**: objects can be explicitly aligned to a set of labels, or the user can simply       ignore the labels and let Series, DataFrame, etc. automatically align the data for you in computations. </br>
  * Powerful, flexible **group by** functionality to perform split-apply-combine operations on data sets, for both               aggregating and transforming data. </br>
  * Make it **easy to convert** ragged, differently-indexed data in other Python and NumPy data structures into DataFrame         objects. </br>
  * Intelligent label-based **slicing, fancy indexing, and subsetting** of large data sets. </br>
  * Intuitive **merging** and **joining** data sets. </br>
  * Flexible **reshaping** and pivoting of data sets. </br>
  * **Hierarchical** labeling of axes (possible to have multiple labels per tick). </br>
  * Robust IO tools for loading data from **flat files** (CSV and delimited), Excel files, databases, and saving / loading       data from the ultrafast **HDF5 format**. </br>
  * **Time series**-specific functionality: date range generation and frequency conversion, moving window statistics, moving     window linear regressions, date shifting and lagging, etc. </br>
 
Many of these principles are here to address the shortcomings frequently experienced using other languages / scientific      research environments. For data scientists, working with data is typically divided into multiple stages: munging and          cleaning data, analyzing / modeling it, then organizing the results of the analysis into a form suitable for plotting or      tabular display. pandas is the ideal tool for all of these tasks.

Some other notes

  * pandas is **fast**. Many of the low-level algorithmic bits have been extensively tweaked in Cython code. However, as         with anything else generalization usually sacrifices performance. So if you focus on one feature for your application you     may be able to create a faster specialized tool. </br>
  * pandas is a dependency of statsmodels, making it an important part of the statistical computing ecosystem in Python.         </br>
  * pandas has been used extensively in production in financial applications. </br>
