
           Yogar-CBMC v0.1 
                 November 2017

* Usage (SV-COMP 2018) *

To run Yogar-CBMC, use the following command-line from this directory:

>./yogar-cbmc --no-unwinding-assertions --32 <inputfile>

where  <inputfile>  is the filename to be verified. 

The counterexample will also be written in "witness.graphml".

To run Yogar-CBMC for SV-COMP benchmark, use the following command-line from this directory:

>PYTHONPATH=. benchexec -r "sv-comp17" -t Concurrency --no-container yogar-cbmc.xml

We assume that benchexec has been installed already.

* Environement

This binary of Yogar-CBMC runs on Ubuntu 16.04 of 64bit.
