# dashboard-with-excel

# HR Data Dashboard with Excel

This repository contains an Excel file (`HR DATA_Excel with dashboard(version 1).xlsb (1).xlsx`) that includes raw HR data and an interactive dashboard designed to visualize key employee metrics. The dashboard provides insights into active employees, termination reasons, ethnic diversity, average tenure, regional distribution, and more.

## File Description
The file `HR DATA_Excel with dashboard(version 1).xlsb (1).xlsx` is an Excel workbook originally created in `.xlsb` (Excel Binary Workbook) format for performance optimization and later converted or copied to `.xlsx`. It consists of:
- **Raw Data**: Employee-related data such as status, termination reasons, ethnic groups, regions, and tenure.
- **Dashboard**: A visually appealing interface with charts and tables summarizing the HR data.

## Features and Steps Implemented
Below are the steps and features implemented in the Excel file to create the dashboard and analyze the HR data:

### 1. Chart of Total Active Employees
- **Purpose**: Display the total number of active employees.
- **Steps**:
  - Created a Pivot Table from the raw data, filtering by "Employee Status" to include only active employees.
  - Added "Employee Count" to the Values area, set to "Count" aggregation.
  - Generated a Column Chart or Pie Chart to visualize the total active employees.

### 2. Termination Reason Table
- **Purpose**: Summarize reasons for employee terminations.
- **Steps**:
  - Built a Pivot Table using the "Termination Reason" field in the Rows area.
  - Added "Employee Count" to the Values area to count employees per reason.
  - Formatted the table with borders and colors, labeled as "Termination Reason."

### 3. Active by Ethnic Group Table
- **Purpose**: Show the distribution of active employees by ethnic group.
- **Steps**:
  - Created a Pivot Table with "Ethnic Group" in the Rows area, filtered for active employees.
  - Added "Employee Count" to the Values area.
  - Applied Conditional Formatting (e.g., Data Bars) and labeled the table "Active by Ethnic Group."

### 4. Average Monthly Tenure Table
- **Purpose**: Calculate the average tenure of employees in months.
- **Steps**:
  - Built a Pivot Table with "Tenure" in the Values area, set to "Average" instead of "Count."
  - Formatted the numbers as a time-based format (e.g., months).
  - Labeled the table "Average Monthly Tenure."

### 5. Active by Regions Table
- **Purpose**: Display the number of active employees across different regions.
- **Steps**:
  - Created a Pivot Table with "Region" in the Rows area, filtered for active employees.
  - Added "Employee Count" to the Values area.
  - Formatted with distinct colors per region and labeled as "Active by Regions."

### 6. Chart for Bad Hires
- **Purpose**: Visualize employees considered "bad hires" based on criteria like performance or short tenure.
- **Steps**:
  - Defined "Bad Hires" using a specific field (e.g., "Performance" or "Tenure < X months").
  - Created a Pivot Table to filter relevant data, then generated a Bar Chart.
  - Added a title like "Bad Hires Analysis" to the chart.

### 7. Slicers for Interactivity
- **Purpose**: Enable dynamic filtering of charts and tables.
- **Steps**:
  - Inserted Slicers for fields like "Department," "Year," or "Status."
  - Connected all Pivot Tables and Charts to the Slicers using "Report Connections."
  - Positioned Slicers prominently on the dashboard with consistent styling.

### 8. Dashboard Creation
- **Purpose**: Consolidate all visualizations into an interactive dashboard.
- **Steps**:
  - Added a new worksheet named "Dashboard."
  - Arranged charts and tables (e.g., Total Active Employees chart at the top, tables below).
  - Added main and sub-titles using fonts and colors for a polished look.
  - Applied a unified color scheme, borders, and visual effects for readability and aesthetics.

## Tools and Skills Used
- **Excel Features**: Pivot Tables, Charts, Conditional Formatting, Slicers.
- **Optional**: Basic VBA scripts for automation (if applicable, depending on complexity).

## Usage
1. Open the file `HR DATA_Excel with dashboard(version 1).xlsb (1).xlsx` in Microsoft Excel.
2. Navigate to the "Dashboard" sheet to explore the visualizations.
3. Use the Slicers to filter data interactively.

## Notes
- The dashboard assumes the raw data includes relevant columns (e.g., Employee Status, Termination Reason, Ethnic Group, Region, Tenure). Adjust the Pivot Tables if your data structure differs.
- For further customization, modify the Pivot Tables, Charts, or Slicer settings as needed.

## Contributing
Feel free to fork this repository, enhance the dashboard, or suggest improvements via pull requests!

---
