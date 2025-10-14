# Tech Industry Layoffs Analysis

## Overview
This project analyzes tech industry layoff data to understand patterns, trends, and impacts across different companies and sectors. The analysis includes visualizations of layoff distributions, sector impacts, and company-specific insights.

## Requirements

### Python Version
- Python 3.8 or higher

### Required Libraries
```txt
pandas>=1.3.0
numpy>=1.20.0
matplotlib>=3.4.0
seaborn>=0.11.0
```

## Project Structure
```
analysis-2/
│
├── analysis.ipynb        # Main analysis notebook
├── tech_layoffs.csv     # Dataset file
├── Final Report.txt     # Detailed analysis report
├── requirements.txt     # Project dependencies
└── README.md           # Project documentation
```

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd analysis-2
```

2. Create and activate a virtual environment (optional but recommended):
```bash
python -m venv venv
.\venv\Scripts\activate
```


## Usage

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `analysis.ipynb` in your browser

3. Run all cells in sequence to reproduce the analysis

## Analysis Components

- Data cleaning and preprocessing
- Layoff status distribution analysis
- Company status analysis (public/private)
- Top companies with highest layoffs
- Industry sector impact analysis
- Visualization of key findings

## Key Visualizations

- Pie chart of clear vs unclear layoff numbers
- Bar chart of company sectors
- Horizontal bar chart of top 10 companies with highest layoffs
- Bar plot of top 5 sectors with highest layoffs

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License
[MIT License](LICENSE)

## Contact
For questions or feedback, please open an issue in the repository.

---
*Note: Make sure to update the dataset path in the notebook if you store it in a different location.*