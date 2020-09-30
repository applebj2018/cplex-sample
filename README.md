# cplex-sample
a cplex samle , find optimal locations of new stores, copied ibm cplex jupyter notebook sample, the sample couldn't run , debug it and make it works.
the error is, string run out of range, I guess the chicago public data changed it format, json data add or deleted some data, made the sample doesn't work.

libraries = build_libraries_from_url('https://data.cityofchicago.org/api/views/x8fc-8rcq/rows.json?accessType=DOWNLOAD',
                                   name_pos=12,
                                   lat_long_pos=16) 
                                   
                                   my change, lat_long_pos=16, original it is 18. 
