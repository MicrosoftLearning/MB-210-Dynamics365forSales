---
lab:
    title: 'Lab: Make a playbook'
    module: 'Module 2: From Lead to Opportunity'
---

Module 2: From Lead to Opportunity
==================================

## Practice Lab – Make a playbook

Scenario
--------

You are a functional consultant configuring Dynamics 365 for Sales for World
Wide Importers. The sales department has recently finalized a set of best
practices based on past experiences and analysis of successful sales. As part of
the best practices, each opportunity must have a set of related activities
required to be completed. The set of specific activities to be completed
depending on the size of the opportunity. In this lab, you will create playbook
templates and activities and use the playbooks within the application.

**Important Note:** This lab will provide you with an actual Dynamics 365 tenant
and licenses for the Power Platform applications you will be using in this
course. You will only be provided with one tenant for the practice labs in this
course. The settings and actions you take within this tenant do not roll-back or
reset, whereas the virtual machine you are provided with does reset each time
you close the lab session. Please be aware that Dynamics 365 is evolving all the time. The
instructions in this document may be different from what you experience in your
actual Dynamics 365 tenant. It is also possible to experience a delay of several
minutes before the virtual machine has network connectivity to begin the labs.

Exercise 1 – Create Playbook Template
-------------------------------------

In this exercise, you will create two Playbook Templates: one for Opportunities
with $1,000,000 or more estimated budget, and one for Opportunities with
estimated budget between $500,000 and $1,000,000.

### Task 1 – Create Playbook Categories

In this task you will create Playbook Categories.

1.  Go to your **Sales Hub** application.

2.  Click on **Sales** at the bottom of the left menu to navigate the site map. Select **App Settings** from the list.

3.  Locate and click **Playbook Categories** under the **Playbook management** settings.

4.  Click **+ New**.

5.  Enter **[my prefix] Over $1,000,000** for **Name** and click **Save**.

6.  Click **+ New** again.

7.  Enter **[my prefix] $500,000 to $1,000,000**. For **Name** and click **Save**.

### Task 2 – Create Playbook Template One

In this task, you will create a Playbook Template and add Playbook Activities.

1.  In the left menu, select **Playbook Templates**.

2.  Click **+ New**.

3.  Start typing your prefix into the **Category** field. The playbook categories you just created will appear. Select **[my prefix] Over $1,000,000** for **Category**. The **Name** will autofill.

4.  Enter **10** for **Estimated Duration (days)** and click **Save**.

5.  Locate the **Select Record Types** section on the Playbook Template form.

6.  Select **Opportunity** and click **>**.

7.  Go to the **Playbook Activities** sub-grid and click **+ Add Activity**.

8.  Select **Phone Call**.

9.  Enter **[my prefix] Introduction and Meeting Setup** for **Subject**.

10. Enter **2** for **Relative Due Date (Days).** The number of days is counted
    from the launch date of the Playbook.

11. Select **04:00 PM** for **Relative Due Time**.

12. Select **30 Minute** for **Duration**.

13. Select **High** for **Priority** and click **Save**.

14. Click **+ Add Activity** again and select **Appointment**.

15. Enter **[my prefix] Lunch Meeting with Stakeholders** for **Subject**, **4** for
    **Relative Start Date (Days),** select **11:00 AM** for **Relative Start Time (Hours),** **4** for **Relative End Date (Days),** select **02:00 PM** for
    **Relative End Time (Hours),** select **High** for **Priority**, and click
    **Save**.

16. Click **Publish**. Playbooks will not be available to your Users until they
    are published.

17. Click **Publish** when prompted to confirm the publishing.

### Task 3 – Create Playbook Template Two

In this task, you will create a Playbook Template and add Playbook Activities.

1.  From the left menu, select **Playbook Templates**.

2.  Click **+ New**.

3.  Start typing your prefix into the **Category** field. The Playbook Categories you created will appear. Select **[my prefix] $500,000 to $1,000,000** for **Category**. The **Name** will autofill.

4.  Enter **10** for **Estimated Duration (days)** and click **Save**.

5.  Locate the **Select Record Types** section.

6.  Select **Opportunity** and click **>**.

7.  Go to the **Playbook Activities** sub-grid and click **+ Add Activity**.

8.  Select **Phone Call**.

9.  Enter **[my prefix] Introduction** for **Subject**.

10. Enter **4** for **Relative Due Date (Days).**

11. Select **03:00 PM** for **Relative Due Time**.

12. Select **30 Minutes** for **Duration**.

13. Select **Normal** for **Priority** and click **Save**.

14. Click **Publish**.

15. Click **Publish** again to confirm the publishing.

Exercise 3 – Using Playbooks
----------------------------

In this exercise, you will use the Playbook Templates you created.

### Task 1 – Using Playbook One 

1.  Go to your **Sales Hub** application.

2.  Return to the **Sales** section of the app by clicking **App Settings** in the bottom left menu.

3.  Locate and click **Opportunities.**

4.  Click **+ New**.

5.  Enter **[my prefix] Over Million** for **Topic**, **1200000** for **Budget Amount**, and
    click **Save**.

6.  Click on the **Launch Playbook** button located in the command bar.

7.  Locate the **[my prefix] Over $1,000,000** template. You can use the search bar to search for your prefix if necessary. Select the template by clicking to the left of the template name so that the row is highlighted. Then click **Launch**. 

8.  Click **Related** and select **Playbooks**.

9.  You should see the Playbook you launched. Click on the **[my prefix] Over 1,000,000**
    Playbook.

10. The Playbook will show more information, including when it was started, the
    estimated close date, the related record, and completed activities. Click to
    open the **Phone Call** activity from  the **Playbook activities** subgrid.

11. Select the User you are logged in for **Call From** by typing in your prefix. Select the contact record for **Jane Doe** for
    **Call To**. Click **Mark Complete**.

12. You will be taken back to the Playbook.

13. The **Completed Activates** will now show **50% complete**.

### Task 2 – Using Playbook Two 

3.  Locate and click **Opportunities.**

4.  Click **+ New**.

5.  Enter **[my prefix] Half a Million** for **Topic**, **500000** for **Budget Amount**,
    and click **Save**.

6.  Click on the **Launch Playbook** button located in the command bar.

7.  Locate the **[my prefix] $500,000 to $1,000,000** template. You can use the search bar to search for your prefix if necessary. Select the template by clicking to the left of the template name so that the row is highlighted. Then click **Launch**. 

8.  Click **Related** and select **Playbooks**.

9.  You should see the Playbook you launched. Click on the **[my prefix] $500,000 to $1,000,000** Playbook.

10. The Playbook will show more information including when it was started, the
    estimated close date, the related record, and completed activities. Click to
    open the **Phone Call** activity.

11. Select the User you are logged in for **Call From** by typing in your prefix. Select the **Jon Doe** contact record for
    **Call To**. Then click **Mark Complete**.

12. You will be taken back to the Playbook.

13. The **Completed Activates** will now show **100% complete**.

14. Click on the **Complete as** button located on the commend bar.

15. Select **Successful**.

16. The Playbook will be marked as completed and the playbook and all its
    activities will become read only.
