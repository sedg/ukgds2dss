# UKGDS2DSS

Convert [UKGDS][SEDG] spreadsheet [data][ukgds] into [OpenDSS][] scripts.

## Usage (Python 2):

    >>> from ukgds2dss import *
    >>> ukgds2dss("/path/to/ehv3.xls", "/path/to/ehv3.dss")

## Usage (Python 3):

    >>> from ukgds2dss-py3 import *
    >>> ukgds2dss("/path/to/ehv3.xls", "/path/to/ehv3.dss")
    >>> # To convert all co-located XLS files to DSS format.
    >>> ukgds2dss_all() # the default path is set to your current working directory
    >>> ukgds2dss_all(path = "/path/to") # or specify the path to your input files

## Command-line use for ukgds2dss-py3.py (Python 3):
    >>> # Convert all XLS files in the directory to DSS format.
    >>> python ukgds-py3.py all
    >>> # Convert the chosen file to DSS format.
    >>> python ukgds-py3.py filename # e.g. python ukgds-py3.py ehv1
    
[SEDG]: http://www.sedg.ac.uk/ukgds.htm
[ukgds]: https://github.com/sedg/ukgds
[OpenDSS]: http://smartgrid.epri.com/SimulationTool.aspx
