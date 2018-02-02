---
layout: page
title: S&O StartUp
---

Analytics Health Check

Click on the drop down menu in the top left of Analytics
If they have multiple IDs in the view column, check with the client to make sure you are using the correct ID view [ or check the linked accounts section in Adwords to see which view they have synced with Analytics ]
Select the correct Account/ID
On the bottom left hand side of analytics, Select the Admin Gear Icon
Under Account
Click Account Settings > Enable “Google Product & Services” and “Benchmarking” and “Techincal Support”
Leave the other  boxes as is
Under Property:
Click on Property Settings
Verify that the Default URL is correct
Make sure That Default View is selected [ should match the view name ]
Check Industry Category, if none apply select Shopping
Enable “Enable Demographics and Interest Reports”
Click on Tracking Info
Referral Exclusion List
Add the following Referral exclusions:
Domainname.com
Paypal.com
Shared SSL, if needed
Click on AdWords Linking
Verify that the link group is connected to their AdWords ID
If you NEED to link the accounts: Enable All Webstie Data > Link Accounts
Under View:
Click on View Settings
Verify View ID is the correct ID we are using
Verify Website URL is Correct
Verify Timezone matches the website's location
Click on Ecommerce Settings
Verify Ecommerce is enabled
If this is not enabled, we will be unable to track conversions
Enter in Hubspot: “Ecommerce Tracking is Currently Running” or “Just Enabled Ecommerce Tracking”
If this is enabled, go to the left hand side of Analytics > Click on Conversions (flag icon) > Ecommerce > Product Performance
The Graph should have activity
If NOT, we need to find out why
And Enter in Salesforce: “Ecommerce NOT tracking activity in Google Analytics”
Under the Graph, click on the blue primary dimension that says “Product SKU”
Now we need to identify what the product SKU is; e.g. ID, MPN. So copy one of the Product SKUs listed in Analyitcs and go to Merchant Center.
In Merchant Center > go to Products > List > search for Item ID. > Click on the product that comes up for the search > Scroll down to information provided to us.
Make a note of the product SKU that is getting picked up. That format/data of the SKU you searched should match a product data field; i.e. ID, MPN, or SKU. (When setting up this account in S&O, you will import products based off of this format).
If the Product SKU from Analytics is not listed in Merchant Center, ask the customer to add the SKU in their feed.
For Shopify accounts, check to see if they have a variation. If they have a variation, what we are trying to do will not work because, you cannot add a SKU to a variation.
If you are enabling Ecommerce, perform a test sale to make sure data is pulling in on the graph as listed in the above step.
