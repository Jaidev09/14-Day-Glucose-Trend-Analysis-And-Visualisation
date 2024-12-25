# Blood Glucose Percentile Visualization

This project visualizes blood glucose measurements using percentiles for each time of day. The visualization includes reference lines to indicate in-range and out-of-range values, making it easier to understand blood glucose trends.

## Project Files

- **PDF of Line Chart**: A visual representation of blood glucose percentiles.
- **PBIX File**: Power BI file containing the data and visualization.
- **Jupyter Notebook Code**: Python code for data processing and percentile calculation.
- **Dataset**: CSV file containing blood glucose measurements.

## Process

1. **Get the Data**:
   - Import the dataset into Python using pandas.
2. **Split Date and Time**:
   - Split the date and time into separate columns using pandas.
3. **Calculate Percentiles**:
   - Compute 5th, 25th, 50th, 75th, and 95th percentiles using pandas.
4. **Create Visualization**:
   - Import the processed data into Power BI.
   - Create a line chart with time of day on the x-axis and blood glucose percentiles on the y-axis.
   - Use dashed lines for 95th and 5th percentiles, solid lines for 25th, 50th, and 75th percentiles.
   - Add shading between percentile lines for visual clarity.
   - Label the percentile lines directly on the chart and hide the legend.
   - Add reference lines for the values 80 and 180 mg/dL.

## Instructions

1. **Clone the Repository**:
   ```sh
   git clone <[repository_url](https://github.com/Jaidev09/14-Day-Glucose-Trend-Analysis-And-Visualisation.git)>
2. **Run the Jupyter Notebook to process data and calculate percentiles**:
   ```sh
   jupyter notebook <14-DAY GLUCOSE TREND>.ipynb
3. **Open the PBIX File in Power BI to view and interact with the visualization.**
4. **View the PDF to see the final line chart visualization.**

