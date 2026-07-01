# Semi-Automated Disposal Tool
A tool designed to streamline the monthly processing of Enel's asset disposal reports.

PURPOSE OF THE TOOL
ENEL's monthly disposal report is prepared on the first business day of each month, covering assets disposed of during the previous month. In addition, around the middle of the month, a review report is carried out to highlight any errors or omissions. The tool's purpose is to speed up both the review phase and the final report drafting phase.

BASIS OF THE TOOL
The tool's logic is based on the document "Disposal report v9 01072026," adapted to guide the AI that built the tool in configuring its parameters.

TOOL OVERVIEW
The tool consists of three main files:
1. disposal_ui_v2_CHECK.html – Handles the first processing phase: it ingests the file of disposed assets and the file of actual asset costs, both downloaded from ENEL's ServiceNow, then analyzes and processes them according to the rules set out in the guide.
2. disposal_amendments.html – Used to record any amendments requested by ENEL Asset Management.
3. disposal_report_tool_FINALE (1).html – Handles the final processing phase, generating the definitive Disposal report from the Excel file produced during the first phase.

HOW TO USE THE TOOL
On the landing page that opens when you click the link, you can upload the disposal file on the left and the asset pricing file on the right. You can also select the month to review, if needed. After clicking "Run Automatic Checks," the tool generates the check file along with a summary of the checks performed. You can then review any issues found and download the processed Excel file. Buttons in the top-right corner let you navigate to the tool's other functions.
The second section covers amendments, where you can enter any changes to specific rows, based on instructions received from ENEL Asset Management.
In the final section, Final Report, you can upload the file previously generated during the check phase and start the final processing step. Any amendments entered in the second section are automatically incorporated.
