---
lab:
    title: 'Lab 2.1: Manage Customers'
    module: 'Module 2: Manage leads and opportunities with Dynamics 365 Sales'
---

Module 2: Manage leads and opportunities with Dynamics 365 Sales
==================================

## Practice Lab 2.1 – Manage customers

As you review the imported leads, you notice that one lead is missing. Apparently, Tom Smith's card wasn't added to the leads file that you imported. You remember talking with Tom at the trade show, and it seemed like a successful opportunity. You eventually find Tom's card and now have to manually enter the lead in Dynamics 365.

1. If necessary, in the site map, go back to **Sales** > **Leads**.
2. On the command bar, select **New**.
3. Enter the following values for the new lead:

    - **Topic-** 12 Airpot XL Coffee Makers
    - **First Name-** Tom
    - **Last Name-** Smith
    - **Job Title-** Cafeteria Manager
    - **Business Phone-** 701 555-8698
    - **Email-** `Tom@tomsbikeski.com`
    - **Company-** Tom's Bike and Ski
    - **Address-** 1987 43rd St N. Seattle, WA 98728

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

Several weeks have passed since you last spoke with Tom Smith about adding products to their stores. At the time, Tom mentioned that the committee that's in charge of the decision had decided not to move forward. But today Tom calls you and says that the committee might be interested in moving forward after all. Tom thinks that it would be helpful if you met the committee in person to introduce yourself and your organization.

1. If necessary, in the site map, go back to **Sales** \> **Leads**.
2. Change the view to **Closed Leads**.
3. Open the closed lead for Tom Smith.
4. On the command bar, select **Reactivate Lead**.
5. After the lead is reactivated, in the **Timeline** pane, select the plus button (**+**), and then, on the menu that appears, select **Phone Call**.
6. Enter the following values for the new phone call:

    - **Subject-** Change of Situation
    - **Direction-** Incoming
    - **Description-** Tom reached out to let me know that the Decision-Making Committee is interested in looking at expanding our product line again.

7. Select **Save and Close**.
9. In the **Timeline** pane, select the plus button (**+**) again, and then, on the menu that appears, select **Appointment**.
10. Enter the following values for the new appointment:

    - **Required Attendees-** Tom Smith
    - **Subject-** Introduction Meeting
    - **Location-** Their Office
    - **Start Time** Tomorrow at 10:00 AM
    - **End Time-** Tomorrow at 11:00 AM
    - **Description-** Initial introduction meeting with Committee.

11. Select **Save and Close**.

### Close the meeting and qualify the lead

You've met with the committee, and the members have indicated that they're interested in moving forward with the expansion of the product line.

1. In the **Timeline** pane, find and select the **Introduction Meeting** appointment.
2. Select the check mark, to **Close Activity**.
3. Make sure that the state is updated to **Completed**, and then select **Close**.
4. On the command bar, select **Qualify** to qualify the lead. A new opportunity record is created and opened.
5. Make sure that the following values are already entered for the opportunity:

    - **Contact-** Tom Smith
    - **Account-** Tom's Bike and Ski

6. In the **Lead to Opportunity Sales Process** BPF, select the **Qualify** phase. You're taken to the original lead record. The record is now read-only.
7. In the BPF, select the **Develop** phase to return to the opportunity record.
5.  Click **Reactivate Lead**.

6.  The Lead will be reactivated, the status will change back to New, and the record
    will become editable.
