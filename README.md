# climate_policy_Yale
This is my Capstone project.

### Project description

This project will explore the effectiveness of global policies (Nationally Determined Contributions) in agrifood systems. Currently, the project has a set up project structure, and basic data cleanign file of global and agricultural greenhouse gas (GHG) emissions.

### Research questions

Have the mechanisms set up under Paris Agreement successfully driven mitigation ambition in agriculture?

### Data 
Data is sources from FAOSTAT and was downloaded on 11/19/2026 from https://www.fao.org/faostat/en/#data/GT.

## Repository strucutre

climate_policy_Yale/
├── README.md                    ← you are here
├── raw_data/                    ← original data, never edited
│   ├── FAOSTAT_data_en_11-19-2026.xls
├── clean_data/                  ← output of 1_data_clean.ipynb
│   └── country_emissions_clean.xlsx
├── figures/ 
│   └── global_emissions_afs_share.png  ← figure comparing total to agrifood GHG emissions globally
└── scripts/                     ← notebooks, numbered in the order they run
    ├── 0_project_setup.ipynb
    └── 1_data_cleaning.ipynb

### Data cleaning
GHG emissions were filtered to include only CO2-eq in order to avoid duplication, duplicated drained organic soil data was removed, data was summed per country and transformed into Gt. Exploratory plot was created to assess the accuracy of the database cleaning performed.
