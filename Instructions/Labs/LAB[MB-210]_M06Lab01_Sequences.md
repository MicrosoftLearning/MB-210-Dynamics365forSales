---
lab:
    title: 'Lab 6.1: Build a sequence'
    module: 'Module 6: Get started with Sales Insights'
---


Module 6: Get started with Sales Insights
==============================

## Practice Lab 6.1: Build a sequence 

Scenario
--------

Sellers suggest that sales could be improved if organizational "best practices" were easier to follow. The sales managers have determined the ideal sequence of sales events for sellers, and they want to enforce best practices by setting up the set of consecutive activities for sellers. To make these practices easily available to sellers to follow during the course of their day, you suggest creating a sequence.

In this lab, we will create a simple sales sequence for your sellers to follow.


### Task 1: Create new sequence

1. Change the area to **Sales Insights settings** using the bottom left &#709; dropdown menu icon.

2. In the **Sales Insights** group, select **Global settings**.

3. In the **Sales accelerator** sub-group, select the **Sequences** tab.

4. If necessary, select **Enable** on the notification to enable worflow for sequences to work properly.

5. If necessary, select **Setup workspace**, then select **Quick setup**. Select **Publish** on the flyout pane.

5. On the **Sequences** tab, select **+ New sequence**.

6. You have the option to create a sequence from a number of common templates. You can explore the templates available. When you're ready, select **Start from blank.** 


### Task 2: Create basic information about the sequence

1. Assign name, description and choose the type of table that the sequence will be available for.

2. In the Sequence Name text box, type the sequence name, **[my prefix] Sequence.** 

3. In the **Description** text box, enter sequence description: "This is a test sequence for my test customer."

4. In **Record type**, select Lead (if it is not already selected).

4. Click **Next**.


### Task 3: Choose the first activity for seller to take

Choose the first step for your sellers to take. This can be either sending an email, making a phone call or add a task of your own. In our example, we will start with an email. 

1. Underneath the **Sequence start** tile, select the **+** button to add an action or other element.

2. Click on **Send an email**. 

3. For **Title**, enter: **[my prefix] Introduction email**.

4. For **Description** optionally, enter a description: **Introduce lead to the sales team.**

5. If email templates, table specific or global templates, are available in your organization, you can choose an email template. In this case, we will assume that the seller will write their own introduction email.

6. Click **Save**.


### Task 4: Add additional activities for your seller to take

Add additional activities for your sellers to take in an ordered manner,
i.e. seller needs to take the first activity first, then the second and
third and so on.

To persist changes, after adding an activity, click on the **Save** button.

1. Click on the **+** button.

2. Choose the next activity for the seller to take, can be either sending
an email, making a phone call or add a task of your own. Select **Set wait time** to define a time-interval between activities. 

   In our example we will add a time-interval of **1 hour**.

3. Click **Save**.

4. In a similar manner, add a phone call activity. Select the **+** sign and select **Phone call**. For name, type **[my prefix] Follow-up call.** Add a description.

5. Select **Save** on the command bar.


### Task 5: Activate the sequence

To make the sequence available for sellers to use, activate the sequence. 

1. Select **Activate** on the command bar.

2. Select **Activate** in the pop-up. 

3. Your sequence will now have a green bar at the top telling you that the sequence was successfully activated.


## Task 6: Connect the sequence to records

1. Change the area using the bottom left dropdown menu, select the **Sales** area. 

2. Select **Leads** from the site navigation menu.

3. **Open** the Lead you created earlier in the course. It should start with [your prefix]. If you have more than one, select one randomly.

4. Select **Connect sequence** from the command bar.

   The list of available sequences includes sequences created by you and other users for the **Lead** table.

5. Select the Sequence you created (it should start with your prefix) and select **Connect**.

6. A confirmation message appears at the bottom of the page, and the sequence is connected to the selected lead record. Now, sellers who have access to the lead record can see the activities connected with it.
