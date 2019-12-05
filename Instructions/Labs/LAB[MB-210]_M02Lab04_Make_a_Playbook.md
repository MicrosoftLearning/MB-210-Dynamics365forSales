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
and licenses for the Power platform applications you will be using in this
course. You will only be provided with one tenant for the practice labs in this
course. The settings and actions you take within this tenant do not roll-back or
reset. Whereas the virtual machine you are provided with does reset each time
you close the lab session. What’s more, Dynamics 365 is evolving all the time. The
instructions in this document may be different from what you experience in your
actual Dynamics 365 tenant. It is also possible to experience a delay of several
minutes before the virtual machine has network connectivity to begin the labs.

Exercise 1 - Acquire Tenant Information and Connect
---------------------------------------------------

**Note:** If you have already completed a practice recently, the virtual machine
might pick up where you left off and you will not need to login again.  In that
case you can skip ahead to exercise two and resume.

### Task 1 – Connect to the Power platform administration portal

1.  On Virtual machine MB200-Dynamics_Lab, sign in as Admin with the password
    Pa55w.rd if you are not already logged in.

2.  Outside the VM in the online lab interface click Files and choose D365
    Credentials. This will allocate an Office 365 tenant for you to use in these
    labs.  It will display the admin email and password for your tenant.  You
    should copy this information to notepad or similar for your reference.

3.  In MB200-Dynamics_Lab launch Microsoft Edge from the taskbar. By default,
    the browser opens Office 365. Use the O365 credentials you just acquired in
    the previous step to login.

4.  Navigate in the browser to the Power platform admin portal at
    [https://admin.Powerplatform.microsoft.com](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fadmin.Powerplatform.microsoft.com&data=02%7C01%7Cv-juya%40microsoft.com%7C4be5a28c6f1e41eefee808d687ae2dc7%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636845580068684293&sdata=cLrD%2FhTDb5sRbajtFR9RrztfyTDCo0xGS4k8FSxTaIc%3D&reserved=0)

Exercise 2 – Create Playbook Template
-------------------------------------

In this exercise, you will create two Playbook Templates, one for Opportunities
with \$1,000,000 or more estimated budget, and one for Opportunities with
estimated budget between \$500,000 and \$1,000,000.

### Task 1 – Create Playbook Categories

In this task you will create Playbook Categories

1.  Go to your **Sales Hub** application.

2.  Click on the **Site Map**, click on the **… More Options** button and select
    **App Settings**.

3.  Locate and click **Playbook Categories**.

4.  Click **+ New**.

5.  Enter **Over \$1,000,000** for **Name** and click **Save**.

6.  Click **+ New** again.

7.  Enter **\$500,000 to \$1,000,000**. For **Name** and click **Save**.

### Task 2 – Create Playbook Template One

In this task, you will create a Playbook Template and add Playbook Activities.

1.  Go on the **Site Map** button and select **Playbook Templates**.

2.  Click **+ New**.

3.  Select **Over \$1,000,000** for **Category**. The **Name** will autofill.

4.  Enter **10** for **Estimated Duration (days)** and click **Save**.

5.  Locate the Select **Record Types** section.

6.  Select **Opportunity** and click **\>**.

7.  Go to the **Playbook Activities** sub-grid and click **+ Add Activity**.

8.  Select **Phone Call**.

9.  Enter **Introduction and Meeting Setup** for **Subject**.

10. Enter **2** for **Relative Due Date (Days).** The number of days is counted
    from the launch date of the Playbook.

11. Select **04:00 PM** for **Relative Due Time**.

12. Select **30 Minute** for **Duration**.

13. Select **High** for **Priority** and click **Save**.

14. Click **+ Add Activity** again and select **Appointment**.

15. Enter **Lunch Meeting with Stakeholders** for **Subject**, **4** for
    **Relative Start Date (Days),** select **11:00 AM** for **Relative Start
    Time (Hours), 4** for **Relative End Date (Days),** select **02:00 PM** for
    **Relative End Time (Hours),** select **High** for **Priority**, and click
    **Save**.

16. Click **Publish**. Playbooks will not be available to your Users until they
    are published.

17. Click **Publish** when prompted to confirm the publishing.

### Task 3 – Create Playbook Template Two

In this task, you will create a Playbook Template and add Playbook Activities.

1.  Go on the **Site Map** button and select **Playbook Templates**.

2.  Click **+ New**.

3.  Select **\$500,000 to \$1,000,000** for **Category**. The **Name** will
    autofill.

4.  Enter **10** for **Estimated Duration (days)** and click **Save**.

5.  Locate the Select **Record Types** section.

6.  Select **Opportunity** and click **Add**.

7.  Go to the **Playbook Activities** sub-grid and click **+ Add Activity**.

8.  Select **Phone Call**.

9.  Enter **Introduction** for **Subject**.

10. Enter **4** for **Relative Due Date (Days).**

11. Select **03:00 PM** for **Relative Due Time**.

12. Select **30 Minute** for **Duration**.

13. Select **Normal** for **Priority** and click **Save**.

14. Click **Publish**.

15. Click **Publish** again to confirm the publishing.

Exercise 3 – Using Playbooks
----------------------------

In this exercise, you will use the Playbook Templates you created.

### Task 1 – Using Playbook One 

1.  Go to your **Sales Hub** application.

2.  Click on the **Site Map**, click on the **… More Options** button and select
    **Sales**.

3.  Locate and click **Opportunities.**

4.  Click **+ New**.

5.  Enter **Over Million** for **Topic**, **1200000** for **Budget Amount**, and
    click **Save**.

6.  Click on the **Launch Playbook** button located in the command bar.

7.  Select the **Over \$1,000,000** template and click **Launch**.

8.  Click **Related** and select **Playbooks**.

9.  You should see the Playbook you launched. Click on the **Over 1,000,000**
    Playbook.

10. The Playbook will show more information including when it was started, the
    estimated close date, the related record, and completed activities. Click to
    open the **Phone Call** activity.

11. Select the User you are logged in for **Call From**, select **Jane Doe** for
    **Call To**, and click **Mark Complete**.

12. You will be taken back to the Playbook.

13. The **Completed Activates** will now show **50% complete**.

### Task 2 – Using Playbook Two 

1.  Go to your **Sales Hub** application.

2.  Click on the **Site Map**, click on the **… More Options** button and select
    **Sales**.

3.  Locate and click **Opportunities.**

4.  Click **+ New**.

5.  Enter **Half a Million** for **Topic**, **500000** for **Budget Amount**,
    and click **Save**.

6.  Click on the **Launch Playbook** button located in the command bar.

7.  Select the **\$500,000 to \$1,000,000** template and click **Launch**.

8.  Click **Related** and select **Playbooks**.

9.  You should see the Playbook you launched. Click on the **\$500,000 to
    \$1,000,000** Playbook.

10. The Playbook will show more information including when it was started, the
    estimated close date, the related record, and completed activities. Click to
    open the **Phone Call** activity.

11. Select the User you are logged in for **Call From**, select **Jon Doe** for
    **Call To**, and click **Mark Complete**.

12. You will be taken back to the Playbook.

13. The **Completed Activates** will now show **100% complete**.

14. Click on the **Complete as** button located on the commend bar.

15. Select **Successful**.

16. The Playbook will be marked as completed and the playbook and all its
    activities will become read only.
