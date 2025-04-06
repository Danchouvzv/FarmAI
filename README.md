# Rice Yield Prediction using Machine Learning

## Project Overview
This project focuses on predicting rice yield using machine learning techniques. It combines satellite data, ground measurements, and various environmental factors to build predictive models for rice production.

## Project Structure
```
├── Baseline.ipynb           # Main analysis notebook with linear regression models
├── Baseline 2.ipynb         # Secondary analysis notebook
├── ricep.csv               # Primary rice dataset
├── rice_Xy.csv             # Extended rice dataset with features
├── Ricex_prepared2.csv     # Preprocessed rice data
├── Satellite/              # Satellite imagery data
├── Google Earth/           # Google Earth data
├── Related Work/           # Related research and literature
└── requirements.txt        # Python dependencies
```

## Data Sources
- Ground measurements of rice fields
- Satellite imagery
- Google Earth data
- Environmental parameters

## Features
- Linear regression models
- Feature engineering
- Data visualization
- Cross-validation
- Performance metrics analysis

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/RiceYieldPrediction.git
cd RiceYieldPrediction
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## Usage
1. Open `Baseline.ipynb` in Jupyter Notebook
2. Run cells sequentially to:
   - Load and preprocess data
   - Train models
   - Evaluate performance
   - Visualize results

## Dependencies
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

## License
This project is licensed under the terms included in the LICENSE file.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.