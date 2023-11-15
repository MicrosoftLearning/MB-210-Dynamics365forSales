## Practice Lab 3: Manage leads and opportunities with Sales Insights 

Scenario
--------

## Exercise 3.1: Work with the opportunity pipeline view 

Your manager indicates concern about some of your team's open opportunities having less than desirable predictive opportunity scores. You want to take a look at all the open opportunities and see a high-level view of their predictive scoring.

1. Navigate to **Opportunities.**

2. You will see the Opportunitiy pipeline view, which shows all open opportunities mapped on a graph. The x-axis shows the estimated close date and the y-axis shows the predictive opportunity score.

3. Each opportunity is mapped by a circle. The size of the circle represents the estimated revenue. The color of the circle represents the relationship health grade.

4. The opportunities most at risk are represented by the biggest orange circles closest to the axis intersection. Hover over the big orange circle at the bottom of the pipeline chart. The record name will appear and should read **2 Cafe Duo Espresso Machines for Fabrikam.**

5. Click on the circle. The opportunity record will open in a pane on the right side of the screen. Here, we can easily view details about the opportunity, including the Contact, Purchase Process, Purchase Timeframe, and its associated Activities.

6. This pane can be customized to best fit your working style. Select the **Customize layout** button (looks like a magic wand). Toggle the radio buttons to customize your layout. When done, make sure **Compact header** is *off* and **Extended width** is *on.*

7. Details about the opportunity can be entered right here in the Opportunity pipeline view. Under the Purchase process field, change **Unknown** to **Committee.**

8. You just got a call that Fabrikam needs another 2 weeks to come to a decision. Let's track the incoming call as an activity, and then update the estimated close date.

9. Find the Timeline in the opportunity pane and click the plus sign to add an activity. Select **Phone call** as the Activity type.

10. For subject, enter "Needs to delay close date."

11. Change the Direction to **Incoming.** The Call From and Call To fields will switch. Select **Save and close.**

12. Select the carrot next to the Owner field. Update the **Est. close date** to 2 weeks after the original date.

13. Click **Save.**

14. The opportunity pipeline view will update to reflect the new opportunity close date (the circle representing 2 Cafe Duo Machines for Fabrikam will move to the right).

## Exercise 3.2: Create a sequence for a low-grade lead

One of the sellers on your team has expressed difficulty making contact with a lead. You want to help coach them on effective ways to improve their relationship with the customer and nurture the deal to a successful close. You suggest two ways to help the seller:

1) Create a sequence and add it to the seller's lead record to help the seller follow clear steps
2) Monitor key performance metrics like relationship health score and predictive lead scoring

Let's take action on these two steps to help close the lead.

1. Navigate to **Sales accelerator** in the left menu. This is the Sales accelerator workspace.

2. Look through the **work list** in the left side of the screen. The work list displays a list of records that are assigned to you or to a security role that you're part of. It offers a quick view of records to pay attention to.

3. Click the **filter** button and check **Unopened.**

4. Select the **Sort** button and select **Score.** Then select **Lowest on top.**

5. On each record in the work list, take a look at the following:
    - Blue dot to denote it as unopened
    - The number of the lead score and corresponding color to represent its grade (green, yellow or orange)
    - The task beneath the Lead name with the option to call, mark as complete, or assign it to someone else
  
6. Reset your filters. Use the search bar to search for one of the following leads: **Rachel Michael**, **Gerald Stephens**, or **Lilly Pyles.** Once the record in the work list is opened, it disappears from the view because it is no longer unopened.

7. Under the Lead name, switch from the **Sales trial** form to the **Sales Insights** form. On the lead record in the Sales accelerator workspace, take a look at the following:
   - The Up Next widget, showing the next task and its due date.
   - The timeline.
   - The lead score. Hover over the factors below the lead score grade. Show the insights behind the lead scores.
   - Relationship health.
   
8. Switch to the **Relationship analytics** tab. Take a look at the following:
   - Summary, with key insights computed from previous years.
   - Relationship health.
   - Client's contacts and your colleagues.
   - Customer interactions.
   - Hourly investment.
   - Email engagement.
   - Email send/receive ratio.
   - Relationship activities.
  
9. Let's take action on this lead to improve our predictive lead score.
    - Expand the **Qualify** stage of the business process flow.
    - Change Purchase Timeframe to **Next quarter.**
    - Change Estimated Budget to **40,000.**
    - Change Purchase Process to **Individual.**

10. **Save** the record. Scores are refreshed every 24 hours, so you will not see the lead score update in real time. Congratulations! You have taken action to improve the lead score for this lead.
  
## Exercise 3.3: Create new sequence

Your sales teammate expresses that when he's spoken with their lead, the lead expressed that they prefer phone calls and meetings to emails. You decide that the existing sequence, which relies heavily on email communication, doesn't work for some customers. You decide to build a new sequence that focuses more on in-person selling styles. Instead of creating a new sequence from blank, you'll use the existing lead nurturing sequence, create a copy, and make edits.

1. Change the area to **Sales Insights settings** using the bottom left drop-down menu icon.

2. In the **Sales Insights** group, select **Global settings**.

3. In the **Sales accelerator** sub-group, select the **Sequences** tab.

4. If necessary, select **Enable** on the notification to enable workflow for sequences to work properly.

5. If necessary, select **Setup workspace**, then select **Quick setup**. Select **Publish** on the flyout pane. Then select the **Sequences** tab again.

5. Find the **New lead nurturing** sequence. This is the sequence currenly in use for lead records. Select the sequence and select **Create a copy.**

6. Under Sequence name, enter "In-person lead nurturing." In the Description, enter "Nurture outreach series for prospecting new leads, focusing on calls and meetings."

7. Select **Save and edit.**

## Exercise 3.4: Configure a sequence

Let's take a look at the sequence and replace steps where sellers sent emails with calls or meetings.

1. Delete the first email step under **Sequence starts here.**

2. Select the plus sign to add a new step where the email step used to be. Select **Make a phone call.**

3. Under Title, enter "Introduction call." Under Description, enter "Introduce seller and organization."

4. Under that step, select the plus sign and add a new Email step.

5. Under Title, enter "Thank you email." Under "Description", enter "Thank customer for their time and provide your contact information in writing."

6. Keep the Set wait time step.

7. Delete the Send a reminder email. Replace with a **Phone call** step titled "Follow-up call." In the description, enter "Follow up after initial introduction and schedule in-person meeting."

8. Add a step below Follow-up call to **Complete a task.** The title should be "Schedule meeting."

9. Leave the other steps the same.

10. **Save** the sequence.

11. **Activate** the sequence. (Check **I understand** and then **Activiate** again if necessary.)

## Exercise 3.5: Connect the sequence to records

1. Change the area using the bottom left dropdown menu. Select the **Sales** area. 

2. Select **Leads** from the site navigation menu.

3. Use the search bar to search for the lead you opened in the previous task. You can start by typing in their first or last name.

4. Open the record.

5. Select **Connect sequence** from the command bar. The list of available sequences includes sequences created by you and other users for the **Lead** table.

6. Select the Sequence you created called "In-person lead nurturing." Select **Connect**.

7. A confirmation message appears at the bottom of the page, and the sequence is connected to the selected lead record. Now, sellers who have access to the lead record can see the activities connected with it.

8. Under the lead's name, select the carrot next to **Lead.** Switch to **Sales Insights** to view the record using the Sales Insights form. Refresh the Up next widget. It should now read **Set up introduction call.**

9. Expand the step and mark as complete.

10. The next sequence will appear in the Up next widget. There is a countdown to the time you need to complete.

11. Congratulations! You have made a new sequence and connected it to a record.
