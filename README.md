# linecount_history
Script to generate line count statistics for a git repository

Usage
=====

    $ python linestat.py --filetypes=cpp,h --output=linestat.txt

.. will write **linestat.txt** in current folder for every commit on 'master' since the first, counting the lines
in *.cpp and *.h files recursively from the current folder. The linestat.txt is formatted like this:

    2018-01-01\t12:01\t500\n

Note: by cd:ing into a subfolder of the repository, you can do a primitive exclusion.

