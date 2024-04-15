# POM ACO Network Evaluation GitHub Repository

This repository hosts the code and analysis for the POM ACO Network Evaluation project. The purpose of this project is to analyze the provider networks of the Physicians Organization of Michigan Accountable Care Organization (POM ACO) to enhance patient care quality and reduce healthcare expenditures. Our analysis covers the composition and performance of POM ACO's provider networks throughout Michigan, with the goal of identifying strategic improvements that align with Medicare's performance metrics.

## Repository Structure

- **data/**: This directory contains the datasets used in the analyses. Due to privacy and confidentiality agreements, access to these data files may be restricted. Please ensure you have the appropriate permissions before accessing or using this data.

- **Data Cleaning and Analysis.ipynb**: This Jupyter Notebook contains all preprocessing and data cleaning steps necessary to prepare the data for further analysis. It includes handling missing values, normalizing data, and extracting relevant features that are crucial for accurate downstream analysis.

- **Network Composition Analysis.ipynb**: This notebook provides a detailed analysis of the network composition of POM ACO. It explores the structure and demographics of the provider network, assessing trends and changes over time to offer insights into the network's evolution and its impact on performance metrics.

- **Spend pattern & Quality care.ipynb**: This notebook investigates the relationship between spending patterns and quality of care within the POM ACO network. The analysis aims to identify spending efficiencies and their correlation with improved patient care outcomes, guiding strategic financial decisions within the network.

## How to Use This Repository

1. **Clone the Repository**: Start by cloning this repo to your local machine or download it as a ZIP file.
   ```
   git clone https://github.com/your-username/pom-aco-evaluation.git
   ```

2. **Set Up Your Environment**:
   - Ensure you have Python installed, preferably Python 3.8 or above.
   - Install the required libraries and dependencies:
     ```
     pip install -r requirements.txt
     ```

3. **Explore the Notebooks**:
   - Open and run the Jupyter Notebooks in order, starting with `Data Cleaning and Analysis.ipynb` to prepare your data.
   - Proceed with `Network Composition Analysis.ipynb` and `Spend pattern & Quality care.ipynb` for deeper insights.

4. **Review the Data**:
   - Navigate to the `data/` directory to understand the datasets used for the analyses.
   - Due to data sensitivity, ensure compliance with data use agreements and permissions.

## Contributing

Contributions to this project are welcome. Please adhere to this project's `Code of Conduct` while contributing. For major changes, please open an issue first to discuss what you would like to change. Make sure to update tests as appropriate.

- **Fork the Repository**: Create a personal fork of the project on GitHub.
- **Clone the Fork**: Work within your fork and implement the desired changes.
- **Submit a Pull Request**: Push your changes back up to your fork on GitHub and submit a pull request so that we can review your changes.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contact

If you have any questions or would like to contact the team, please [file an issue](https://github.com/your-username/pom-aco-evaluation/issues) on GitHub.

This README provides a comprehensive guide for anyone interested in understanding or contributing to the POM ACO Network Evaluation project. For detailed technical steps or analysis questions, refer to the individual Jupyter Notebooks provided in the repository.
