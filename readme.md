# Clearing the Skies: An In-Depth Look at Factors Behind Airline Delays

## Overview
This capstone project analyzes airline delay patterns using advanced data analytics and machine learning techniques to help airlines and airports optimize their operations and improve customer experience. The project examines various delay factors including weather, security, mechanical issues, and their interconnected impacts on flight operations.

## Project Structure

- `dataset/`: Contains the dataset used for analysis.
- `documents/`: Contains the documents used for analysis.
- `code.ipynb`: Contains the main code used for analysis.

## Analysis Files
```
├── code.ipynb                 # Main analysis file
├── question1.ipynb           # Flight cancellation prediction analysis
├── question2.ipynb           # Delay pattern analysis
├── question3.ipynb           # Root cause classification
├── question4.ipynb           # Delay duration prediction
├── question5.ipynb           # Cascading delay analysis
├── question6.ipynb           # Airport clustering analysis
├── question7.ipynb           # Time series forecasting
├── question8.ipynb           # Feature importance analysis
```
## Documents
- [Project Paper](documents/project-paper.pdf)
- [Presentation](documents/presentation.pdf)

## Key Features
- Predictive modeling for flight delays and cancellations
- Classification of delay root causes
- Time series analysis of delay patterns
- Airport clustering based on delay characteristics
- Seasonal trend analysis
- Feature importance evaluation

## Technologies Used
- Python 3.11
- Key Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - Prophet (for time series)
  - Keras/TensorFlow

## Models Implemented
1. Random Forest Classifier
2. Gradient Boosting Regressor
3. Decision Tree Classifier
4. Support Vector Machines
5. K-Means Clustering
6. Prophet Time Series Model

## Key Findings
- Identified primary factors contributing to flight delays
- Developed predictive models with significant accuracy
- Discovered seasonal patterns in delay occurrences
- Created airport clusters based on delay characteristics
- Analyzed cascading effects of delays

## Data Processing
The project utilizes the Airline Delay Cause dataset, which includes:
- Flight details (carrier, airport, routes)
- Delay categories (weather, carrier, NAS, security, late aircraft)
- Temporal information (year, month)
- Quantitative metrics (arrival delays, cancellations)

## Visualization Examples
The project includes various visualizations:
- Feature importance plots
- Seasonal trend analysis
- Delay distribution by carrier
- Airport clustering visualizations
- Time series forecasts

## Installation and Usage
1. Clone the repository
2. Install required packages:
```bash
pip install -r requirements.txt
```
3. Run Jupyter notebooks:
```bash
jupyter notebook
```
4. Start with `code.ipynb` for the main analysis

## Future Improvements
- Integration of real-time weather data
- Implementation of deep learning models
- Development of interactive dashboards
- Addition of more granular delay predictions
- Integration with airport operational systems

## Contributors
- Ankith Gundeboina
- Avinash Appineni 
- Pavan Kumar Pula

## Acknowledgments
- Dataset provided by [Bureau of Transportation Statistics](https://www.transtats.bts.gov/ot_delay/OT_DelayCause1.asp?20=E)
- Special thanks to [Dr. Sarah Quintanar](https://dataanalytics.unt.edu/people/dr-sarah-quintanar.html) for providing the guidance and support.
- [University of North Texas](https://www.unt.edu/) for support and resources

---
© 2024 Pavan Kokkura. All Rights Reserved.

