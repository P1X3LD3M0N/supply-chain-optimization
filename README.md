## Project Title: Supply Chain Optimization

### Description
This project focuses on optimizing supply chain operations, specifically involving transportation and production decisions. It uses mathematical modeling to minimize costs and efficiently allocate resources across different facilities. The optimization results are visualized to show how products flow through the supply chain over time.

### Objectives
- Develop a mathematical model to represent the supply chain.
- Minimize transportation and production costs while meeting demand.
- Visualize the optimized decisions to understand the flow of goods across different nodes in the supply chain.

### Project Structure
The project is implemented in a Jupyter Notebook and is structured as follows:

1. **Mathematical Model**: 
   - Variables `x` and `y` represent transportation and production decisions.
   - The objective function minimizes the total cost.

2. **Solution Extraction**:
   - After solving the optimization problem, the results for `x` (transportation) and `y` (production) are extracted.

3. **Data Visualization**:
   - The results are visualized using `matplotlib` to display the transportation and production schedules.

### Requirements
To run this project, you'll need the following Python packages:
- `numpy`
- `matplotlib`
- `scipy`

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/P1X3LD3M0N/supply-chain-optimization.git
   cd supply-chain-optimization
   ```
   
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook sc_opt.ipynb
   ```

3. Run all cells to execute the optimization and view the results.

### Usage
- Modify the supply chain parameters within the notebook to fit your specific use case.
- Run the optimization model to generate results.
- Use the visualizations to analyze how the decisions affect the overall supply chain performance.

### Acknowledgements
- Thanks to Arizona State University's CSE 550 course for guidance and support in developing this project.
