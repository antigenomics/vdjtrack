# VDJtrack pipeline

An approach to evaluation of clonotype sampling in immune repertoire profiling time courses.

Contents:

* ``data/`` the folder can be populated with data used in present study by running ``fetch_data.sh``
* ``code/`` all code used in this study
* ``example.Rmd`` and ``example/`` a small example illustrating application of VDJtrack to monitor Yellow Fever Virus-specific clonotype induction at 2nd week post vaccination in a group of 6 volunteers

For comparing samples from different donor cohorts see the ``code/DLI_compare.Rmd`` template. Alternativey one can use ``example.Rmd`` with pooled samples by specifying CDR3s from samples of interest in the ``annotations.txt``.