# Pitcher Throw Analysis: Biomechanics

This project analyzes the relationship between shoulder energy transfer and pitch speed in baseball pitchers. By utilizing biomechanical data, the goal is to explore whether higher shoulder energy transfer correlates with increased pitch velocity. Additionally, the project aims to identify inefficient throwing mechanics that may lead to performance issues or potential overuse injuries.

## Project Overview

### Objective

- **Correlation Analysis**: Investigate the relationship between shoulder energy transfer and pitch speed using linear regression.
- **Inefficiency Detection**: Identify pitches where high shoulder energy transfer does not correspond to expected pitch speeds, suggesting mechanical inefficiencies.

### Dataset

The dataset used for this project contains key biomechanical markers for pitchers. You can access and download the POI dataset from [OpenBioMechanics](https://www.openbiomechanics.org).

## Requirements

To run this analysis, you'll need the following Python libraries:

- pandas
- numpy
- matplotlib
- scikit-learn
- scipy

You can install them using pip:

```bash
pip install pandas numpy matplotlib scikit-learn scipy
```

## How to Use

1. Clone the repository:

    ```bash
    git clone https://github.com/akberShah076/pitcher-throw-analysis.git
    cd pitcher-throw-analysis
    ```

2. Download the POI dataset from [OpenBioMechanics](https://www.openbiomechanics.org) and save it as `poi_metrics.csv` in the project directory.

3. Open the Jupyter Notebook `Pitcher_Throw_Analysis_BioMechanics.ipynb` in your preferred Python environment (e.g., JupyterLab, Google Colab).

4. Follow the instructions in the notebook to perform the analysis.

## Analysis Breakdown

1. **Linear Regression**: Fit a linear regression model to determine the relationship between shoulder energy transfer and pitch speed.
2. **Pearson Correlation**: Calculate the Pearson correlation coefficient to quantify the strength of the relationship.
3. **Box Plot**: Visualize the distribution of shoulder energy transfer in high-velocity vs. low-velocity pitchers.
4. **Bootstrap Analysis**: Validate the significance of the observed differences between high-velocity and low-velocity pitchers.
5. **Inefficiency Detection**: Identify pitches with high shoulder energy transfer but unexpectedly low pitch speeds, suggesting mechanical inefficiencies.

## Results

The analysis identified a moderately strong positive correlation (Pearson r = 0.65) between shoulder energy transfer and pitch speed. Additionally, 12.17% of the pitches (50 out of 411) exhibited inefficiencies where high shoulder energy transfer did not result in the expected pitch speed, which could indicate mechanical issues or inefficiencies in the kinetic chain.

## Contributing

If you'd like to contribute to the project, feel free to open issues or submit pull requests. Any improvements or new ideas are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Let me know if you'd like to adjust any further details!
