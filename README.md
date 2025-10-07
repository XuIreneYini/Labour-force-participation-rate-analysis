# OECD Labour Force Analysis

## Project Overview

This project analyzes OECD labor force participation data, comparing trends between the USA and the EU-27 from 2018 to 2024.
 Data sourced from the OECD's employment indicators.

## File Structure

```
├── code/
│   └── analyze_data.ipynb        # Jupyter Notebook containing the analysis
├── data/
│   ├── raw_data.csv              # Raw OECD data
├── output/
│   └── participation_rate.png    # Output visualization
├── LICENSE                       # Project license
└── README.md                     # Project documentation
```

## Environment Setup

### Install Dependencies

Make sure you have Python and pip installed. Run the following command to install dependencies:

```bash
pip install -r requirements.txt
```

## How to Run

1. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open `code/analyze_data.ipynb` in Jupyter and execute each cell in order.

## Analysis Details

- Data Cleaning: Extracts necessary information from raw data.
- Visualization: Plots labor participation trends for the USA and the EU.

## Key Findings

- Both the US and EU labor participation rate declined during the pandemic but has been recovering.
- The overall labor participation rate in the EU is 15% lower than that in the US.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
```
