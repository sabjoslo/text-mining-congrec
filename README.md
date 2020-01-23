These data were assembled for a project on political speech, with Sabina Sloman, Daniel Oppenheimer and Simon DeDeo at Carnegie Mellon University. For more details or to cite the data source, please email ssloman@andrew.cmu.edu.

These are pre-processed text data from the [U.S. Congressional Record](https://www.gpo.gov/fdsys/), a set of publicly-available transcripts of the proceedings of the U.S. Congress, accessed by us with the help of the [congressional-record project](https://github.com/unitedstates/congressional-record). This data set contains all speeches from the House in 2017. dem_dat.feather contains all speeches by Democratic members, while repub_dat.feather contains all speeches by Republican members.

The data frames contain three columns:
- `speaker` is the name of the speaker, identified using a customized regex.
- `date` is the date of the speech, in "%Y-%m-%d" format.
- `speech` is the text of the speech, coerced to lowercase.

Much existing work has done natural language processing using data from the Congressional Record (e.g. [Diermeier, Godbout, Yu & Kaufmann (2012)](https://www.jstor.org/stable/41485863), [Jensen, Naidu, Kaplan & Wilse-Samson (2012)](https://www.jstor.org/stable/41825364?casa_token=scN-slrQvDEAAAAA:nSWIGwA1lzeDhP9e-qKKqID2sHHkGI36jTWq8FKcnfeTZjkF54Opu981p_4wG4H5cRFowIrQDPKH-Cu4nigygBXiEjl88JCCnZzJyyNBVuCJj2oTXZg&seq=1#metadata_info_tab_contents), [Lauderdale & Herzog (2016)](10.1093/pan/mpw017) and [Gentzkow, Shapiro & Taddy (2019)](https://doi.org/10.3982/ECTA16566)). It is a rich data source for understanding how issues and language characterize different parties, different politicians and different points in time. 
