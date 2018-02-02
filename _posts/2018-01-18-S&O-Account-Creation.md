---
layout: page
title: Sales & Orders StartUp Process
---

S&O Account Creation

Verify that you are logged into all three Google Services within the same browser (AdWords, Analytics, Merchant Center). This will allow you to authenticate the account to that one email address.
Click Add New Account in S&O
Enter the necessary details:
Account Name
For consistency please use domain name as the Account name
Enable “Enable Account”
Access Rules: you can leave unchecked
Timezone: select timezone
SQL Server: Production -3
Iron Que: 2
Account Type: Full Access
Import Product Types: Weekly
Import Day: Default Sunday
Pricing Tool Enabled: leave unchecked
Run Frequency: Weekly
Phone Number: Optional
Domain Name
Min CPC – leave default $0.01
Max CPC Bid – leave default $0.99
Margin: get from Salesforce
Country: Select Country
Product Limit - leave default
Import Products For Country: select country
SKU Mapping: Choose based off of what Analytics picks ups as the Product SKU
Commerce Provider: Select platform
Retail Category: Select Retail category
S&O Services: Select Advanced unless DIY
Customer Type: Select Customer type
Click ‘Create Account’
Do NOT double click this button, otherwise you will duplicate the account
Once the account is created, click on the settings gear icon
Choose Google Connections tab
Enter the IDs for Google AdWords, Google Analytics, and Google Merchant Center.
Save details
Click Authenticate
Campaigns and Products will import automatically
For Campaigns that are not ours, please disable them
Campaign Manager
Click Create Campaign
Campaign Name: Shopping | Primary
Status: Enabled
Country of Sale: Select Country
Campaign Priority: Medium
Local Ads - Leave Default
Search Partners: No
Locations: Select Target Country
Exclude Location - Leave Default
Proximity targeting – Leave default
Default Bid: $0.50
Device Settings
Mobile Bid Modifier: -50% (negative)
Daily Budget: $10.00
Delivery Method: Accelerated
Click Create Campaign button
Now Create a second campaign - the penny/catch-all campaign
Campaign Name: Shopping | All
Status: Enabled
Country of Sale: Select Country
Campaign Priority: Low
Local Ads - Leave Default
Search Partners: No
Locations: Select Target Country
Exclude Location - Leave Default
Proximity targeting – Leave default
Default Bid: $0.01
Daily Budget: $5.00
Delivery Method: Accelerated
Click Create Campaign
In AdWords: click on the All Campaign > Click into the ad group
Change “Everything else in all products” from excluded to $0.01
In S&O, Go to the Add Products Tab in campaign Manager
Add Products to: Select “Shopping | Primary” Campaign
Scroll down to Modify Bids Section and click on the red “Post All” Button
Go to the Pending Tab
Select the white “Post All” button to add all new products to AdWords
Refresh the page and make sure no products are left in Pending
Check in AdWords that all products were added. Go to Tools > Change History > Select Date Range: Today
Next You May need to run Jobs
If an Account is targeting multiple countries, you must create a separate S&O account for each country.
You will need to assign a different email address to each country and their S&O Account.
Then you will need to add this email address to the client's Analytics, AdWords, and Merchant Center
