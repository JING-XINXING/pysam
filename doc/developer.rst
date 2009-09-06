*****************
Developer's guide
*****************

Code organization
*****************

The top level directory is organized in the following 
directories:

pysam
   Code specific to pysam

samtools
   Original and unmodified source code from :term:`csamtools`. Use 
   :file:`setup.py` to obtain the latest code.

tests
   Examples and data for testing

Importing :term:`csamtools`
***************************

Running :file:`setup.py` will import the csamtools source code. 
The command::

   python setup.py import PATH

where ``PATH`` points to a :term:`csamtools` source directory. For example::

   python setup.py import ~/samtools-0.1.6

Note that files will not be overwritten. To import all anew, 
delete all :file:`*.c` and :file:`*.h` files in the :file:`samtools`
directory first. 




