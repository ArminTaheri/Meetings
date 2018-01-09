# CCC-Axis Meeting
*January, 2018*

## Agenda Items
1. Status update
1. Setting a regular meeting schedule
1. Milestones and goal setting
1. CCC-Axis paper


## Updates

### Data Transfer/Storage
1. Hard drives
1. Bandwidth


### Data Visualization
1. Recreated basic plots in qEEGt (@armintaheri add link here)

#### Open Questions
1. How exactly is is the correlation map interpolated?
    1. What values are being interpolated?
    1. What is the mapping from electrode label -> scalp positions
    1. How should color maps be inputted?
    1. What are the default color maps?
1. What is the upper and lower limit for the line plot Y axis? global Min/Max?
1. For multi-line plots in the narrow band study, is there predefined set of line colors?
1. For the broad band study, what do the matrix rows/column correspond to?
1. For Raw narrow band, what files are used to create the colored MRI slices? What is used as intensity?
1. For each of the 12 types of studies what visualization should be used on them?
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
1. Should each study type (CROSS, ETC, PHA) open a tabbed visualization where each tab corresponds to each type of compatible visualization?
    1. If not how would you like to decide which visualization to use for a particular study type?
1. What are the exact band interval values?


### qEEGt in CBRAIN
1. (@laletscaria please add link to current implementation)


## Code Products
1. Platform Independent Visualization Tool (PIVT)
1. S3FS as a sparse data provider in developing world
  - Bandwidth in China?
  - Bandwidth in Cuba?


## Next Steps
