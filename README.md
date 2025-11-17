## Data
The data is pulled from multiple sources, including: 
- [NOAA](https://www.ncei.noaa.gov/pub/data/swdi/stormevents/csvfiles/)
- [Open-Meteo](https://open-meteo.com/en/docs/climate-api)
- ... add the rest here as we use them

The initial csv files from NOAA were manually downloaded and stored in the `raw_data` folder that can be found at [this Google Drive link](https://drive.google.com/drive/folders/1tomaJ-4OtBFpR6in9xoU5PeI1HgVMP8G?usp=drive_link). It contains csv data disaster events (including floods) from multiple states during 1950 - 2025.

You don't need to manually add or use the `raw_data` csv files, they were used for the initial data curation. The final data to use is `data/flooding_events_augmented.csv`.

## Models

Nothing here just yet