# Cons-Test

## Repository structure
- **RunModel.R**  
  - Code for the agent based model.
  - Sources landscape files from `StylizedLandscape.R` and precipitation data from `PrecipTimeseries.R` to create the initial landscape and generate precipitation scenarios.
  - To reproduce experiments from the manuscript, run ABM for `conditions.rds`.
  - ⚠️ Runs may take a long time: running all three scenarios with one setting takes ~45 minutes.  

- **GeneratePlots.R**
  - Can be used to reproduce all experiments from the manuscript
  - 📂 Full data for reproducing visualizations *without* re-running the model across all conditions: [Google Drive link](https://drive.google.com/file/d/1G6POSfm8SaYC4ZBgtwkPUq5TDhat1wRN/view?usp=sharing)  

## How to use

1. Clone this repository to your local machine:
  ```bash
  git clone 
  ```

2. Run the agent-based model: Run `RunModel.R` 





# Citation

If you use this code or dataset in your work, please cite:  

