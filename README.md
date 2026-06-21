# Lab-Referral-Recommendations

An interactive Excel dashboard that recommends the best referral labs based on user-selected criteria. Built for lab analysts and healthcare operations to reduce manual comparison and speed up referral decisions.

<img width="2441" height="2417" alt="Lab Referral Recommendation img" src="https://github.com/user-attachments/assets/21ee4378-4c2c-4184-ad9a-e573ddb65bae" />

## Key Features
- Dynamic Filtering: Select test type Cito/Routine, exam name, and referral day.
- Top 3 Recommendations: Displays the best 3 labs ranked by a weighted final score.
- Detailed Lab Info: Shows price, running schedule, TAT, and pickup service availability for each recommended lab.
- Visual Comparison: Bar chart comparing prices across labs for the selected test and bar chart comparing TAT across labs for the selected test.
- Extended Options: Table listing 4th-ranked labs and below for additional alternatives.
  
## How It Works
1. User inputs filter criteria in the dashboard controls.
2. Excel formulas and data tables calculate scores based on price, TAT, schedule fit, and pickup availability.
3. Results update automatically to show ranked recommendations and charts.
4. All data is sourced from a structured lab database sheet within the workbook.

<img width="400" height="225" alt="Lab Referral Recommendation gif" src="https://github.com/user-attachments/assets/c581496d-dd7b-47ac-8692-4be5d9ee7076" />

   
## Tech Stack
- Microsoft Excel: Power Query, Pivot Tables, INDEX-MATCH/XLOOKUP, conditional formatting
- Data: Dummy Historical lab referral dataset including pricing, TAT, and service details
  
## Use Case
Helps lab teams quickly identify the most cost-effective and time-efficient referral labs, improving turnaround time and operational efficiency.
