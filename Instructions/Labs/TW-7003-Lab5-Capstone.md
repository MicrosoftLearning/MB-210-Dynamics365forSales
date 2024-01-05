TW-7003: Optimize the Sales Process with Dynamics 365 Sales
==============================

## Lab 5: Capstone

Overview
--------
In this workshop, you will create your own solution to the stated problems.  This workshop is open-ended by design. Use this time to practice what you need and don’t be afraid to use your trainer for help when you get stuck.

**Note:** If you are working in a shared training environment, please name any assets you create with a prefix (either a prefix of a group member or a new team prefix) as part of the name to reduce confusion.  For example, you could name a new business process flow *Team Green Sales Process.*

Scenario
--------
You are implementing Dynamics 365 Sales for First Up Consultants.  First Up is a graphics design company that provides services like website design, brochures, logo design, add campaigns, etc.  They typically target small and mid-market organizations that do not have the capacity or staff to handle these operations on their own.  First Up targets both new and existing customers.

The company has changed providers for their product catalog and needs a new one configured.  There is no logical path for migrating the catalog. It will need to be configured manually per the following specifications:

- Different prices are needed for different regions.  The regions are Eastern, Western, South, North.
- Discounts are provided on single products.
- Design services are sold in hourly blocks.  They can be sold as a single hour, 5-hour blocks, 10- hour blocks.  
-	Bundles are only of single items.
-	Products can be sold separately and as bundles.

The products are as follows:
- Logo design
- Website design
- Brochure
- Ad campaign

The products can be sold in bundles. The available bundles are as follows:
- **Bundle 1:** Logo design, website design, and brochure
- **Bundle 2:** Logo design, website design, and ad campaign
- **Bundle 3:** Logo design, website design, brochure, and ad campaign

First Up want to be able to leverage the product catalog easily as part of their sales order processing. They intend to use Opportunities, Quotes, Orders, and Invoices.  

Bonus scenario 1
--------
Once an Opportunity has been closed (regardless of if it was won or lost), First Up want to reach out to the customer and ask about their experience.  They want to capture general information such the customer’s satisfaction level with the process, as well as if there is anything that could have been improved.  

Bonus scenario 2
--------
As a user of the system, you want to easily be able to view your relevant information in a single space.  You want to be able to see your sales pipeline, your Accounts, Leads, and Opportunities.   This will only be accessible by you. 

