Copyright (c) RTLCores LLC. 2010

LongFellow
==========
LongFellow is a set of Python scripts used to document Verilog RTL designs. It
contains the following scripts:

* PortExtractor
    Parses a Verilog file searching for module definitions and extracts
    port information and associated comments used for documentation.

* GitInfo
    Gets various pieces of information from a Git repository which are used
    to populate fields in the document. Things like SHA, commit date etc.
