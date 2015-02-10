## This is the SwissLeaks/Lagarde List data repository

This a handy repository for data dumps commonly known as Swiss Leaks or The Legarde List.

For more info see here: http://en.wikipedia.org/wiki/Lagarde_list

For now all we have is the ICIJ data, but more can be added as desired.

All data will be attributed as best possible. Anonymous data will be marked as such and original licensing will be preserved.


### New Submissions

If you wish to submit new data, please submit a pull request with a section added to the README containing the provenance of the data along with any caveats and the terms of license. Closed licenses are less likely to be accepted than open licenses.

If there is interest in a shared scripts directory for data manipulation, please open an issue and we will set up a separate repository. 

### ICIJ data

This data is provided under license from the International Consortium of Investigative Journalists as listed below. 

These are not represented by the ICIJ to be a full listing of the leak files.

More info on the datafiles here:
    - https://offshoreleaks.icij.org/about/caveats
    - https://offshoreleaks.icij.org/about/credits
    - http://www.icij.org/offshore/icij-releases-offshore-leaks-database-revealing-names-behind-secret-companies-trusts
    - http://www.icij.org/blog/2013/06/offshore-leaks-database-faqs

#### Licensing of the ICIJ Data

The licensing from the ICIJ is listed on the download page is CC BY-NC 3.0.

The CC BY-NC 3.0 license means:

    - You can share and adapt this work as you want.
    - You must give appropriate credit and indicate changes made to the data
    - You cannot use for commercial purposes without permission or add additional restrictions.

See this for more info

http://creativecommons.org/licenses/by-nc/3.0/

Please cite The International Consortium of Investigative Journalists when you use information from the database in publications and other works.


#### ICIJ_20140123 directory

The ICIJ_20140123 directory is the contents of the downloadable zipfile csv.zip from: https://offshoreleaks.icij.org/search

The zipfile unpacked like so:

    swiss_leaks_data$ unzip csv.zip 
    Archive:  csv.zip
      inflating: csv 2014 01 23/countriesNW.csv  
      inflating: csv 2014 01 23/edges_1DNW.csv  
      inflating: csv 2014 01 23/node_countriesNW.csv  
      inflating: csv 2014 01 23/nodesNW.csv  

The top level directory was renamed to ICIJ_20140123 and the files were modified to use UNIX style Line Feed ending w/o Carriage Returns before checkin.

