### EX10 [PROJECT] Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 27-04-2024
### AIM: To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
### Description: 
<div align = "justify">

### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:
```
Name: D.vishnu vardhan reddy
Register No: 212221230023
```
![326148171-563e2378-9c07-4478-aab2-f9ba8bb61917](https://github.com/RuchithaReddy28/WDM_EXP10/assets/93427261/a44bba5f-f404-4e78-ab4d-c62212624eb2)
![326148180-70b5c021-0de6-4dbe-8503-d545e5072c57](https://github.com/RuchithaReddy28/WDM_EXP10/assets/93427261/cecbdd5c-72e8-4e3f-a25d-3cf368f27845)
![326148192-1344c1a2-e0c1-442f-871a-6a63cba73ee2](https://github.com/RuchithaReddy28/WDM_EXP10/assets/93427261/d2b25eb2-faf6-433d-b097-5b955a84dbd5)

### Result:
Thus, sentimental analysis for twitter data using Rapidminer is done successfully.
