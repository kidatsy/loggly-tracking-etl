For storing a transformation taking Loggly CSV dls and turning them into actually useful files

Included is a small node script to clean up dirty/corrupted csv files. It is super rough-and-ready, so make sure to clean it up. This clean-up script was only necessary because Microsoft horribly mangled the original output from Loggly when I saved the files in Excel. NEVER do that.

~~Using Clover ETL to do the actual transformation.~~ Trying to learn Clover ETL was too much. Going to with good old Pentaho Kettle.