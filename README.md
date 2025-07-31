# Personal Finances Dashboard (KNIME Workflow)

This repository contains a KNIME workflow for analyzing and visualizing personal finance data. The dashboard provides interactive charts, spending analysis, and insights to help you better understand and manage your finances.

## Features

- Data cleaning and preprocessing
- Categorization of expenses and income
- Time series analysis of spending and savings
- Interactive visualizations (bar charts, pie charts, line graphs, etc.)
- Summary statistics and financial insights

## Requirements

- [KNIME Analytics Platform](https://www.knime.com/downloads) (version 4.4 or higher recommended)
- Personal finances dataset (CSV or as specified in the workflow)

## Getting Started

1. **Download or Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/personal-finances-knime.git

1. **Open KNIME Analytics Platform**  
   - Download and install KNIME if you haven’t already from [here](https://www.knime.com/downloads).  
   - Launch the KNIME Analytics Platform on your computer.

2. **Import the Workflow**  
   - Go to `File > Import KNIME Workflow...`  
   - Select the file `Personal_Finances_Dashboard.knwf` from this repository.  
   - Choose your destination workspace and click `Finish`.

3. **Configure Data Source (if needed)**  
   - If the workflow uses a local personal finances CSV file, make sure the file path in the `File Reader` or `CSV Reader` node matches the location of your dataset.  
   - Right-click the node (e.g., `File Reader`) and select `Configure...` to update the path if necessary.

4. **Execute the Workflow**  
   - To run the entire workflow, click the green double-arrow button in the toolbar (`Execute all executable nodes`), or right-click the workflow background and select `Execute all`.  
   - Alternatively, right-click individual nodes and select `Execute`.

5. **View the Dashboard**  
   - Right-click the dashboard component node (e.g., `Component View`, `Interactive View`, or similar) and select `Interactive View: ...` to open the dashboard in a new window.

6. **Save and Explore**  
   - Save your workflow and explore the interactive dashboard and results.

---

### Troubleshooting

- If a node fails (red status), right-click and select `View: Error Log` for details.
- Ensure all file paths are correct and required extensions are installed in KNIME.

### License

This project is licensed under the MIT License.
