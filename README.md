# Supply Chain Optimization

This repository contains Python code for optimizing supply chain distribution through linear programming. The objective is to minimize transportation costs from various origin ports to a destination port.

## Versions

### Normal Version
- **Objective**: Minimize costs using average values.
- **Method**: Reads and merges data from Excel sheets, calculates average costs and weights, and uses linear programming with supply and demand constraints.

### Second Version
- **Objective**: Minimize costs with balanced cost estimates.
- **Method**: Uses midpoints between minimum and maximum values for cost estimates, filters and merges plant and warehouse data, and applies additional constraints for refined results.

## Libraries Used
- **Pandas**: For data handling.
- **PuLP**: For optimization.

## Files Included
- **Excel Sheets**: Contain rates, orders, and capacities.
- **Python Scripts**: Implement the optimization models.

## How to Use

1. **Install Dependencies**:
   ```bash
   pip install pandas pulp
   ```

2. **Prepare Data**:
   Place your Excel sheets in the project directory. Ensure they are named correctly as referenced in the scripts.

3. **Run the Scripts**:
   Execute the relevant Python scripts to perform the optimization. The results will be outputted as specified in the scripts.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

