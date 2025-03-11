# Oxford Battery Data Analysis

This repository contains a Jupyter Notebook that explores the Oxford Battery Degradation Dataset, i.e., EIL-MJ1-015 dataset. The analysis aims to understand battery behavior, including capacity fade, state of charge (SOC), and dQ/dV characteristics.

## Atribution

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/anatarajank/Battery-Data-Analysis">Battery Data Analysis</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.linkedin.com/in/anatarajank/">Aravindan Natarajan</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>

## Citation
If you use this repository in your work, please cite using the following:

[Battery Data Analysis, Aravindan Natarajan, https://github.com/anatarajank/Battery-Data-Analysis](https://github.com/anatarajank/Battery-Data-Analysis)

## Project Overview

This project reproduces and expands upon the data analysis presented in the research article:

* **Authors:**  *T. M. M. Heenan, A. Jnawali, M. D. R. Kok, T. G Tranter, C. Tan, A. Dimitrijevic, R. Jervis, D. J. L. Brett, and P. R. Shearing*
* **Title:** An Advanced Microstructural and Electrochemical Datasheet on 18650 Li-Ion Batteries with Nickel-Rich NMC811 Cathodes and Graphite-Silicon Anodes
* **Journal:** Journal of The Electrochemical Society
* **DOI:** [10.1149/1945-7111/abc4c1](https://iopscience.iop.org/article/10.1149/1945-7111/abc4c1)

The analysis utilizes Python and popular libraries like Pandas, NumPy, Matplotlib, and Seaborn to extract insights from the battery data.

## Dataset

The Oxford Battery Degradation Dataset is a valuable resource for battery research, providing electrochemical data from a commercially available 18650-format lithium-ion battery. The EIL-MJ1-015 dataset, used in this project, captures the battery's response to various charge and discharge cycles.

**Dataset Structure:**

This dataset is comprised of two main sections. The first four columns provide a summary of the cycling data, while the remaining columns contain the detailed cycling data itself.  Before further analysis, the dataset requires some cleaning and preprocessing.

## Notebook

The Jupyter Notebook [Oxford_Battery_Data_Analysis_V1.ipynb] (https://github.com/anatarajank/Battery-Data-Analysis/tree/main/jupyter%20notebooks) guides you through the following steps:

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

## Author
Aravindan Natarajan

## License

This project is licensed under the CC BY 4.0 International license. See the `LICENSE` file for details.
