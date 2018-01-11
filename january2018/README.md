# CCC-Axis Meeting
*January, 2018*

## Agenda Items
1. Status update (All)
1. Setting a regular meeting schedule (All)
1. Milestones and goal setting (Shawn, Pedro, Alan)
1. CCC-Axis paper (Jorge)


## Updates

### Data Transfer/Storage
1. Hard drives
1. Bandwidth


### Data Visualization
1. Recreated basic plots in qEEGt (@armintaheri add link here)

#### Open Questions
1. How exactly is the correlation map interpolated?
    1. What values are being interpolated?
    1. What is the mapping from electrode label -> scalp positions
    1. How should color maps be inputted?
    1. What are the default color maps?
1. What is the upper and lower limit for the line plot Y axis? global Min/Max?
1. For multi-line plots in the narrow band study, is there predefined set of line colors?
1. For the broad band study, what do the matrix rows/column correspond to?
1. For Raw narrow band, what files are used to create the colored MRI slices? What is used as intensity?
1. What is the mapping from the following study types to the type of visualization to use?
    1. Raw Narrow Band CROSS 
    1. Z Transform Narrow Band ZCROSS 
    1. Raw Broad Band  BBSP 4 Z Transform Broad Band ZBBSP 
    1. Raw Electrical Tomography Cortex ETC 
    1. Z Transform Electrical Tomography Cortex ZETC 
    1. Raw Electrical Tomography Cortex and Basal Ganglia ETCBG 
    1. Z Transform Electrical Tomography Cortex and Basal GangliaZETCBG 
    1. Raw Electrical Tomography Individual ET
    1. Raw Temporal Correlation COR 
    1. Raw Coherence COH 
    1. Raw Phase PHA
1. What are the exact band interval values?


### qEEGt in CBRAIN
Link to the repo: https://github.com/glatard/qeeg (Private)
* We have verified that this Docker container produces the same results as those provided by Jorge
* Available on the main CBRAIN portal through two Bourreaux: ACE-Docker-1, Guillimin
* Version is kept as `undefined` since there was no version control for the files that were shared -- would be good if we could freeze this version with some tag now that we've verified performance is expected.

## Code Products
1. Platform Independent Visualization Tool (PIVT)
1. S3FS as a sparse data provider in developing world (no link yet)
    - We may be able to ship "private S3" devices on hard drives, and enable the sparse caching and access of this data through the S3FS data provider we're developing.
    - This will avoid bulk downloads of data onto super computers, can provide a solid usecase of write-once devices or drives
    - When accessing external data to China or Cuba, this data provider downloads minimal data required for tasks, so will reduce bandwidth as much as possible


## Next Steps

