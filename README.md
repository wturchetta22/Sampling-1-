## Structure
```
Project
├── .ipynb_checkpoints
│   └── (several notebooks for separate algorithms)  
├── Data
│   └── web-Stanford.txt.zip 
├── Samples
│   └── (sub-directories by sample size and algorithm)
├── Sampling Code
│   └── (one notebook per algorithm)
├── Calculate All Statistics.ipynb
├── Final_Stats.csv
├── README.md
└── Report.ipynb
```
## How-to

### Creating samples

1. Unzip data file
2. Run any of the sampling algorithms found in the "Sampling Code" sub-directory with a specified sample size
3. Generates 5 .csv files to the same directory

### Evaluating samples / calculating D-statistics

1. Run `Calculate All Statistics.ipynb`, note this takes a very long time to run as it does all 80 (5 samples x 4 sample sizes x 4 algorithms) runs at once 
2. Code for specific sampling algorithms is contained within the `.ipynb_checkpoints` folder, however, and there are descriptions and examples therein on how everything was calculated/works.

### Final Report

1. See `Report.ipynb`, note results were saved in `Final_Stats.csv` and then imported and manipulated in the Report notebook
