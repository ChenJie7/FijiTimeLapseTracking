# FijiTimeLapseTracking
Easy manipulation and graphing of a time lapse data after it's been analyzed by trackmate in fiji

The data was mask was manually corrected by humans after cellpose output, this was then passed into a hyperstack in fiji for Labeled image detector to detect the provided masks and pipeline the results onto trackmate using LAP tracker.  

The file generalize contains a made pipeline where given edges, tracktable(Spots), track csv files, it creates a plot of of every track per cell input.
