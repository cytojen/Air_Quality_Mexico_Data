# ATM & MET Traffic Data Analysis for MER and UIZ Stations

This repository contains data files and a Jupyter Notebook for analyzing ATM (Air Traffic Management) and MET (Meteorological) data, specifically focusing on the "MER" and "UIZ" stations. This analysis involves preprocessing and examining traffic and meteorological parameters to derive insights into traffic patterns, environmental impact, and operational conditions for each station.

## Project Structure

- **Data Files**:
  - `raw_ATM+MET_MER.csv`: Raw ATM and MET data for the MER station.
  - `raw_ATM+MET_UIZ.csv`: Raw ATM and MET data for the UIZ station.
  - `atm_met_uiz.csv`: Processed or merged ATM/MET data specific to the UIZ station.
  - `atm_met_mer.csv`: Processed or merged ATM/MET data specific to the MER station.
  - `raw_traffic_MER.csv`: Raw traffic data for the MER station.

- **Notebook**:
  - `MER_UIZ_ATM_MER_TRAFFIC_DATA.ipynb`: A Jupyter Notebook containing the data processing and analysis steps applied to the ATM, MET, and traffic data for both the MER and UIZ stations.

## Usage

### 1. Data Preparation
The data files provided are used within the notebook for preprocessing. Ensure all data files are in the same directory as the notebook.

### 2. Running the Notebook
1. Open `MER_UIZ_ATM_MER_TRAFFIC_DATA.ipynb` in Jupyter Notebook or Jupyter Lab.
2. Run each cell sequentially to load, preprocess, and analyze the data.

### 3. Analysis Objectives
- **Traffic Analysis**: Investigate traffic patterns and variations at the MER and UIZ stations.
- **Meteorological Impact**: Analyze how meteorological conditions affect traffic density and delays at each station.
- **Data Integration**: Merge ATM and MET data to provide comprehensive insights on operational and environmental factors at the station level.

## Dependencies

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib (or other visualization libraries used in the notebook)

Install dependencies with:
```bash
pip install pandas numpy matplotlib
```

## Output

The notebook generates visualizations and statistical summaries, offering insights into the traffic dynamics and their relationship with meteorological conditions for each station.

## License

This project is licensed under the MIT License.

## Contact

For questions or contributions, please contact [Your Name] at [Your Email].
