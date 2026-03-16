**GeoGebra Construction Analyzer**

Overview

GeoGebra Construction Analyzer is a Python tool for extracting, classifying, and analyzing mathematical objects contained in GeoGebra applets (.ggb files). GeoGebra constructions are stored internally as XML descriptions of mathematical objects such as functions, points, segments, and other algebraic or geometric elements. This tool parses the internal structure of GeoGebra files, identifies the objects present in a construction, and organizes this information into structured datasets.
The program can automatically detect and classify mathematical expressions according to common function types (e.g., polynomial, rational, trigonometric, exponential, logarithmic, and others). It also tallies the occurrences of different objects and function types and exports the results to CSV files. These outputs can then be analyzed using spreadsheet software or statistical tools such as Python or R.
This software was developed to support research on function art, where students create visual designs using graphs of mathematical functions in GeoGebra. By automatically extracting and quantifying the mathematical objects used in these constructions, the tool enables large-scale analysis of student-generated GeoGebra artifacts.

Features

* Extraction of mathematical objects from GeoGebra (.ggb) files
* Identification of algebraic expressions in GeoGebra constructions
* Automatic classification of function types
* Counting and tallying of mathematical objects and functions
* Batch processing of multiple GeoGebra files in a folder
* Export of results to CSV format for further analysis

**Requirements**

The program requires Python and the following libraries:

```
python >= 3.9
sympy
pandas
```

Install dependencies using:

pip install sympy pandas

**Usage**

1. Place your GeoGebra .ggb files inside a folder.
2. Update the folder path in the script if necessary.
3. Run the program.

Example:

`python analyzer.py`

The program will process all GeoGebra files in the folder and generate a CSV file containing the extracted objects and counts.

**Output**

The program generates CSV files containing:

* extracted object expressions
* classification of function types
* counts of objects and functions in each GeoGebra construction

These outputs can be analyzed using tools such as Excel, Python, or R.

**Research Applications**

This tool can support several research tasks involving GeoGebra-based mathematical constructions, including: 

* analysis of student-created function art
* investigation of function types used in mathematical designs
* learning analytics studies involving GeoGebra artifacts
* analysis of mathematical structures embedded in digital learning materials

By converting GeoGebra constructions into structured datasets, the program enables large-scale analysis of mathematical objects in technology-enhanced learning environments.

**How to Cite**

If you use this software in research, please cite:

Bautista, G. P. Jr. (2026).
GeoGebra Construction Analyzer (Version 1.0) [Software]. Zenodo.
https://doi.org/xxxxx

**License**

This project is released under the MIT License, which allows users to use, modify, and distribute the software provided that attribution is given to the original author.

**Acknowledgment**

This software was developed as part of research on function art and the analysis of GeoGebra-based mathematical constructions in technology-enhanced learning environments.
