# Dataset

This project uses the **Volve Oil Field Production Dataset**, obtained from Kaggle.

The dataset contains historical daily production and operational data from multiple wellbores in the Volve field, including oil, gas, and water production, wellhead and downhole pressure and temperature, choke size, and operating hours.

### Source

The dataset was obtained from:

**Kaggle:** [Volve Oil Field Production Data]((https://www.kaggle.com/datasets/lamyalbert/volve-production-data))

The dataset is originally associated with **Equinor's Volve field open data**.

### Main Variables Used

* `DATEPRD` — Production date
* `NPD_WELL_BORE_NAME` — Well identification
* `BORE_OIL_VOL` — Oil production volume
* `BORE_GAS_VOL` — Gas production volume
* `BORE_WAT_VOL` — Water production volume
* `AVG_WHP_P` — Average wellhead pressure
* `AVG_WHT_P` — Average wellhead temperature
* `AVG_DOWNHOLE_PRESSURE` — Average downhole pressure
* `AVG_DOWNHOLE_TEMPERATURE` — Average downhole temperature
* `DP_CHOKE_SIZE` — Differential choke size
* `ON_STREAM_HRS` — On-stream hours

### Usage

The dataset is used in this repository for educational and exploratory data analysis purposes. The raw dataset is not included in this repository; users should obtain it from the original source before running the notebook.
