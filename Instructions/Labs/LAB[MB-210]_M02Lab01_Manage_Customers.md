---
lab:
    title: 'Lab 2.1: Manage Customers'
    module: 'Module 2: Manage leads and opportunities with Dynamics 365 Sales'
---

Module 2: Manage leads and opportunities with Dynamics 365 Sales
==================================

## Practice Lab 2.1 – Manage customers

As you review the imported leads, you notice that one lead is missing. Apparently, Tom Smith's card wasn't added to the leads file that you imported. You remember talking with Tom at the trade show. Tom is the President of a bike and ski company, and he is interested in adding new coffee makers in his 6 regional offices. You eventually find Tom's card and now have to manually enter the lead in Dynamics 365.

1. If necessary, in the site map, go back to **Sales** > **Leads**.
2. On the command bar, select **New**.
3. Enter the following values for the new lead:

    - **Topic-** 12 Airpot XL Coffee Makers
    - **First Name-** Tom
    - **Last Name-** Smith
    - **Job Title-** President
    - **Business Phone-** 701 555-8698
    - **Email-** `Tom@tomsbikeski.com`
    - **Company-** Tom's Bike and Ski

4. Select **Save and Close** to save the lead record.

## Qualify and disqualify leads

Now that Tom Smith's lead record has been entered in Dynamics 365, you want to start the lead qualification process to determine the potential for business. You'll first reach out to Tom via a phone call.

### Add activities to records

1. Find and open the lead record for Tom Smith that you created earlier.
2. In the **Timeline** pane, select the plus button (**+**), and then, on the menu that appears, select **Phone Call**.
3. Enter the following values for the new phone call:
    - **Subject-** Initial qualification call.
    - **Description**- Called Tom to discuss the size of their office and amount of coffee makers they might need.
4. Select **Save and Close**.

### Update the Qualify phase and disqualify the lead

While you were on the phone with Tom Smith, you learned that they need to involve a few more decisionmakers in their decision: their Office Manager and Budget Administrator. He indicated that the expense is not in the budget for this quarter, and they don't intend to upgrade their coffee machines now. They want to revisit in the next fiscal period.

You now want to make a note of this information in Dynamics 365.

1. Open the lead record for Tom Smith, and then, in the **Lead to Opportunity Sales Process** business process flow (BPF), select the **Qualify** phase.
2. In the dialog box that appears, set the **Purchase Timeframe** column to *This Year*.
3. Set the **Purchase Process** column to *Committee*.
4. Because Tom indicated that the committee isn't currently interested in moving forward, on the command bar, select **Disqualify** to disqualify the lead. Then, on the menu that appears, select **No Longer Interested**.

### Reopen the lead and capture the phone call activity

Several weeks have passed since you last spoke with Tom Smith about adding products to their stores. At the time, Tom mentioned that the committee in charge of the decision had decided not to move forward. But today Tom calls you and says that the committee might be interested in moving forward after all. Tom thinks that it would be helpful if you met the committee in person to introduce yourself and your organization.

1. If necessary, in the site map, go back to **Sales** > **Leads**.
2. Change the view to **Closed Leads**.
3. Open the closed lead for Tom Smith.
4. On the command bar, select **Reactivate Lead**.
5. After the lead is reactivated, in the **Timeline** pane, select the plus button (**+**), and then, on the menu that appears, select **Phone Call**.
6. Enter the following values for the new phone call:

    - **Subject-** Change of Situation
    - **Direction-** Incoming
    - **Description-** Tom reached out to let me know that the Decision-Making Committee is interested again. 

7. Select **Save and Close**.

8. In the **Timeline** pane, select the plus button (**+**) again, and then, on the menu that appears, select **Meeting**.
9. 
10. Enter the following values for the new meeting:

    - **Required Attendees-** Tom Smith
    - **Subject-** Introduction Meeting
    - **Location-** Their Office
    - **Start Time** Tomorrow at 10:00 AM
    - **End Time-** Tomorrow at 11:00 AM
    - **Description-** Initial introduction meeting with Committee. They discussed that they would like to close 3 weeks from today but are still unsure about the price.

9. Select **Save and Close**.
   
### Close the meeting and qualify the lead

You've met with the committee, and the members have indicated that they're interested in moving forward with the expansion of the product line.

1. In the **Timeline** pane, find and select the **Introduction Meeting**.
2. Select the check mark, to **Close Activity**.
3. Make sure that the state is updated to **Completed**, and then select **Close Meeting**.
4. On the command bar, select **Qualify** to qualify the lead. A new opportunity record is created and opened.
5. Make sure that the following values are already entered for the opportunity:

    - **Contact-** Tom Smith
    - **Account-** Tom's Bike and Ski

6. In the **Lead to Opportunity Sales Process** BPF, select the **Qualify** phase. You're taken to the original lead record. The record is now read-only.

8. In the BPF, select the **Develop** phase to return to the opportunity record.

### Work with the Opportunity

Now, it is time to fill out key details about the opportunity. During the meeting, you and Tom discussed that they would like to close the deal 3 weeks from today. However, they are still unsure about pricing. Let's see if we can use AI by Microsoft Copilot to help us close the deal.

1. Select the **Products** tab.
2. Select **Contoso Coffee Price List** as the Price List.
3. Change Revenue to **System Calculated.**
4. Select **+ Add products.**
5. Change the quantity on the **Airpot XL** product to **6.** Select **Add.**
6. Select **Save to opportunity.**
7. Expand the carrot next to the **Owner** field at the top of the screen. You will notice that Est. revenue has been filled in with the total price of 6 Airpot XL coffee machines.
8. Fill in **Estimated close date** as 3 weeks from today.

You realize that you are able to offer a 10 percent discount as part of a new customer promotion. Let's use Copilot to send an email to Tom Smith letting him know the good news.

1. In the Timeline, select the plus sign and select **Email.**
2. In the **Subject** pane, enter **Your interest in Airpot XLs**.
3. The Copilot pane will open automatically on the right side of the screen. Select **Describe the email you want.**
4. Describe the email you want to send in the text box. (Write something like: "Thank Tom for his time and let him know you can offer a 10 percent discount for new customers.")
5. Click the arrow to submit your prompt.
6. Take a look at the generated email. It looks pretty good, but since you and Tom have a nice rapport, let's change the email's tone to make it friendlier.
7. Click the **Adjust draft** button (looks like 2 sliders) below the generated email.
8. Adjust the tone to **Friendly.**
9. In the text box, add "Tell Tom it was nice to meet him last week."
10. Select **Update.**
11. Take a look at the email. Make any edits as you see fit. When you think it's ready to send to Tom, select **Add to email.**
12. Select **Send.**
13. Take a look at the **Timeline** on the opportunity record. Your email will appear here.

### Close the opportunity as won

Great news - Tom Smith would like to close the deal and has accepted the pricing with the ten percent discount. Let's apply the discount, close the opportunity, and create a quote.

1. Navigate to the **Products** tab.
2. Under **Detail amount**, enter **10** in the Discount (%) field. This will apply a 10 percent discount to the prodcuts listed on the opportunity.
3. The estimated revenue will update to reflect the discount.
4. Select **Close as won** from the top navigation bar.
5. Select **OK** in the dialog box.
6. Congratulations! You've closed your first opportunity. The record becomes read-only and you will see the close as the most recent activity in the timeline.



