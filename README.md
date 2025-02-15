# Railway 

## Problem Statement

This dashboard provides key insights into railway ticket sales, cancellations, delays, and revenue trends. It enables railway operators to understand their customers' travel patterns, identify issues leading to delays and cancellations, and optimize service efficiency. By analyzing ticket sales distribution, delay causes, and refund requests, railway companies can improve passenger experience and operational effectiveness. Since the total delay cases stand at 2,292 and cancellations at 1,880, significant areas for improvement include addressing signal failures, weather disruptions, and staffing shortages.


## Steps Followed 

- Step 1 Data Loading: The dataset (CSV file) was loaded into Power BI Desktop.

- Step 2: Data Profiling: Opened Power Query Editor and enabled "Column Distribution," "Column Quality," and "Column Profile." Selected "Column profiling based on the entire dataset." Identified missing values in "Arrival Delay" and excluded them from calculations.

- Step 3 Data Cleaning & Processing: Removed errors and null values from "Arrival Delay" (less than 1% missing data). Applied transformations to standardize data fields and ensure consistency.

- Step 4 Report Customization: Selected a theme for visualization consistency. Added slicers for Ticket Type, Purchase Mode, Delay Reasons, and Routes, card visuals for Avg. Delay Time, Total Revenue, and Ticket Sales, as well as bar charts for Cancellation Reasons and Delay Causes.

- Step 5 Calculated Columns & Measures: Used DAX to count total ticket sales, summed revenue by class, payment method, and rail card usage, and analyzed average arrival and departure delays.

- Step 6 Final Report Customization: Added text boxes for the railway company name and tagline, inserted the logo for branding, and published the final report to Power BI Service for accessibility.


# Key Metrics

Total Tickets Sold: 31,653

Total Tickets Cancelled: 1,880

Total Delay Cases: 2,292

Ticket Purchase Insights

### [1] Purchase Type Distribution:

Online: 13,132 (41.49%)

Station: 18,521 (58.51%)

### [2] Tickets Sold by Type:

Advance: 17,561

Off-Peak: 8,752

Anytime: 5,340

### [3] Delay Analysis - Top Delay Reasons:

Weather: 758 cases

Technical Issues: 472 cases

Signal Failure: 451 cases

Staff Shortage: 183 cases

Staffing: 172 cases

Weather Conditions: 169 cases

Traffic: 87 cases

### [4] Cancellations & Refunds - Refund Requests:

No: 30,535

Yes: 1,118

### Cancellation Reasons:

Signal Failure: 519 cases

Staffing: 238 cases

Weather: 237 cases

Technical Issue: 235 cases

Traffic: 227 cases

Staff Shortage: 216 cases

Weather Conditions: 208 cases

### [5] Popular & Unpopular Routes

Most Popular Route: Manchester Piccadilly - Liverpool Lime Street (4,628 tickets)

Least Popular Route: Liverpool Lime Street - Birmingham New Street (14 tickets)

### [6] Financial Summary

Total Revenue: $741,921

Total Refund Amount: $38,702

#### Revenue by Ticket Class:

Standard: $592,522

First Class: $149,399

#### Revenue by Payment Method:

Credit Card: $469,511

Contactless: $219,444

Debit Card: $52,966

#### Revenue by Rail Card:

None: $573,697

Adult: $86,330

Disabled: $52,278

Senior: $29,616

#### Revenue & Ticket Trends

Revenue by Purchase Type:

Online: $382,754 (51.59%)

Station: $359,167 (48.41%)

#### Revenue by Month:

January: $205,091

February: $154,118

March: $194,789

April: $187,231

December: $692

#### Tickets Sold by Month:

January: 8,111

February: 7,644

March: 8,117

April: 7,781

### [7] Train Delay Status

On Time: 27,531 cases

Moderate Delay: 1,200 cases

Minor Delay: Not specified

# Report Snapshot (Power BI DESKTOP)


![Image](https://github.com/user-attachments/assets/1b4596d2-5d11-4264-8841-5d79165cd6af)

# Insights & Recommendations

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Customer Trends

Total Tickets Sold: 31,653

A percentage of tickets sold at Station = 58.51% 

A percentage of tickets sold  Online = 41.49%

		thus, a higher number of customers prefer to buy from the station.


### [2] Ticket Type

Number of Advance tickets sold = 17,561

Number of off-peak tickets sold = 8,752

Number of Anytime tickets sold = 5,340


		Advance tickets were the most popular, followed by Off-Peak and Anytime.

### [3] Delay & Cancellation Trends

Average delay in arrival = 15.09 minutes

Average delay in departure = 14.71 minutes

		Signal failure and weather conditions contribute to the majority of cancellations and delays.

### [4] Financial Performance

Total Revenue: $741,921

The highest revenue came from Standard class tickets ($592,522), while First Class generated $149,399.

		Credit Card transactions accounted for the largest share of payments ($469,511).



# Actionable Recommendations

- Increase Online Ticket Sales: Since only 41.49% of sales occur online, offering discounts or promotions could boost digital adoption.

- Reduce Delays: Addressing signal failures and staffing shortages could significantly reduce delays and improve customer experience.

- Improve Customer Satisfaction: Since a significant number of passengers experience moderate delays, improving punctuality could enhance satisfaction levels.

- Optimize Cancellation Policies: Enhancing real-time communication about delays and alternatives may reduce cancellations and refund claims.

- This comprehensive dashboard provides valuable insights into railway operations, helping companies make data-driven decisions to improve efficiency and customer satisfaction.

  ### Dashboard Screan Shot: [Railway.pdf](https://github.com/user-attachments/files/18808803/Railway_SS.pdf)

