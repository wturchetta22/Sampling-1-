## Structure

Project
├── Data
│   └── `web-Stanford.txt.zip` # zipped version
├── Figures
├── Samples
│   └── # sub-directories by sample size and algorithm  
├── Sampling Code
│   └── # one notebook per algorithm
├── `Calculate All Statistics.ipynb`
├── `Final_Stats.csv`
├── `README.md`
└── `Report.ipynb`

## How-to

### Creating samples

1. Unzip data file
2. Run any of the sampling algorithms found in the "Sampling Code" sub-directory with a specified sample size
3. Generates 5 .csv files to the same directory

### Evaluating samples / calculating D-statistics

1. Run `Calculate All Statistics.ipynb`, note this may take a very long time 