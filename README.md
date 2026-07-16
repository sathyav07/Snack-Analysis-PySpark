# McDonald's vs Starbucks Nutrition Analysis using PySpark

## Project Overview
This project uses PySpark to analyze and compare the nutritional values of McDonald's and Starbucks menu items. The datasets are loaded into PySpark DataFrames, and average values of calories, fat, protein, fiber, and sodium are calculated. Based on the analysis, the healthier option is identified.

## Technologies Used
- Python
- PySpark
- Pandas
- Google Colab

## Results

| Metric | McDonald's | Starbucks | Better |
|--------|-----------:|----------:|:------:|
| Average Calories | 368.27 | 356.64 | Starbucks |
| Average Fat | 14.17 g | 16.35 g | McDonald's |
| Average Protein | 13.34 g | 11.47 g | McDonald's |
| Average Fiber | 1.63 g | 2.85 g | Starbucks |
| Average Sodium | 495.75 mg | 57.93 mg | Starbucks |

## Conclusion

The datasets were loaded into PySpark and analyzed. Starbucks had lower average calories, higher fiber, and much lower sodium, while McDonald's had lower fat and higher protein. Based on the overall comparison, Starbucks was identified as the healthier option for the selected nutritional metrics.
