# Oxford Battery Data Analysis

This repository contains a Jupyter Notebook that explores the Oxford Battery Degradation Dataset, specifically focusing on the EIL-MJ1-015 dataset. The analysis aims to understand battery behavior, including capacity fade, state of charge (SOC), and dQ/dV characteristics.

## Project Overview

This project reproduces and expands upon the data analysis presented in the research article:

* **Authors:**  *T. M. M. Heenan, A. Jnawali, M. D. R. Kok, T. G Tranter, C. Tan, A. Dimitrijevic, R. Jervis, D. J. L. Brett, and P. R. Shearing*
* **Title:** An Advanced Microstructural and Electrochemical Datasheet on 18650 Li-Ion Batteries with Nickel-Rich NMC811 Cathodes and Graphite-Silicon Anodes
* **Journal:** Journal of The Electrochemical Society
* **DOI:** [10.1149/1945-7111/abc4c1](https://iopscience.iop.org/article/10.1149/1945-7111/abc4c1)

The analysis utilizes Python and popular libraries like Pandas, NumPy, Matplotlib, and Seaborn to extract insights from the battery data.

## Dataset

The Oxford Battery Degradation Dataset is a valuable resource for battery research, providing electrochemical data from commercially available 18650-format lithium-ion batteries. The EIL-MJ1-015 dataset, used in this project, captures the battery's response to various charge and discharge cycles.

**Dataset Structure:**

This dataset is comprised of two main sections. The first four columns provide a summary of the cycling data, while the remaining columns contain the detailed cycling data itself.  Before further analysis, the dataset requires some cleaning and preprocessing.


## Notebook

The Jupyter Notebook (`Oxford_Battery_Data_Analysis.ipynb`) guides you through the following steps:

1. **Data Loading and Preprocessing:** Cleaning and organizing the dataset for analysis.
2. **Capacity Fade Analysis:** Investigating the battery's capacity decline over cycles.
3. **State of Charge (SOC) Estimation:** Calculating and visualizing SOC changes.
4. **dQ/dV Analysis:** Exploring electrochemical signatures using differential capacity analysis.
5. **Visualization and Insights:** Presenting results with clear visualizations and interpretations.

## Getting Started

1. **Clone the Repository:** `git clone https://github.com/your-username/oxford-battery-analysis.git`
2. **Open the Notebook:** Launch Jupyter Notebook and open `Oxford_Battery_Data_Analysis.ipynb`.
3. **Install Dependencies:** Ensure you have the necessary Python libraries installed (Pandas, NumPy, Matplotlib, Seaborn). You can install them using `pip install pandas numpy matplotlib seaborn`.
4. **Run the Notebook:** Execute the code cells in the notebook to perform the analysis.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
