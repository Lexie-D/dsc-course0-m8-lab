# dsc-course0-m8-lab

## Project Description

This project analyzed avaiation accidents from 1983-2023 to determine and identify patterns in aircraft outcomes that had been collected for those years. I was asked to do this by by an aircraft insurer who was focused on make, model, and professional build aircrafts during the specified year range.  The patterns I primarily focused on were injury rate and destruction of aircraft rate.

## Files Included

- `script.py`: Core analysis script
- 'AviationDataset.csv': Origional dataset
-'USStates_Code': origional dataset
- `Cleaned_AviationData.csv`: Cleaned dataset from 1983–2023
- `figures/`: Contains all generated visualizations
- `README.md`: This file

## Project Overview

This project analyzes aviation accident data between 1983 and 2 023to identify: 
- Aircraft makes and models with lowest injury rates
- Which types of aircrafts tend to be safer (small vs large)
- Aircraft destruction rates
- Phase of flight and weather condition effects on injury and destruction rates

The analysis was conducted to relay this information to a avaition/aircraft insurance insurer in an attempt to better understand the risks of different aircrafts along with other conditions.

Tools used: **Python, Pandas, Seaborn, Matplotlib, Git Bash**

## Key Findings

- **Large aircraft** have lower injury and destruction rates compared to small aircraft.
  -This implies that they are safe than smaller aircrafts.
- **The safest of the small aircraft makes how much lower injury rates than the rest of the small aircraft makes, but with a   mean of 0.20, it's still higher than all large aircrafts as a whole.
- **Climb phase** of flight is the most dangerous for both passenger injury and aircraft destuction.
- **Poor weather (IMC)** significantly increases risk of sever injury and destruction.

## How to Run the Analysis

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/aviation-safety-analysis.git
   cd aviation-safety-analysis

