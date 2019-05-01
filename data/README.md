# ADS Project 1: What made you happy today?
### Data folder

The data directory contains data used in the analysis. This is treated as read only; in paricular the R/python files are never allowed to write to the files in here. Depending on the project, these might be csv files, a database, and the directory itself may have subdirectories.

### Data Structure
```
happydb
└── data
    ├── cleaned_hm.csv
    ├── demographic.csv
    ├── original_hm.csv
    ├── senselabel.csv
    ├── topic_dict
    │   ├── entertainment-dict.csv
    │   ├── exercise-dict.csv
    │   ├── family-dict.csv
    │   ├── food-dict.csv
    │   ├── people-dict.csv
    │   ├── pets-dict.csv
    │   ├── school-dict.csv
    │   ├── shopping-dict.csv
    │   └── work-dict.csv
    └── vad.csv
```

**For schema descriptions of the files, please [click here](https://github.com/rit-public/HappyDB#cleaned_hmcsv)**
