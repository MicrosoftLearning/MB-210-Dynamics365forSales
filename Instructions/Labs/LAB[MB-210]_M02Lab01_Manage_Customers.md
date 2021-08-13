---
lab:
    title: 'Lab 2.1: Manage Customers'
    module: 'Module 2: Manage leads and opportunities with Dynamics 365 Sales'
---


Module 2: Manage leads and opportunities with Dynamics 365 Sales
==================================

## Practice Lab 2.1 – Manage customers

Scenario
--------

World Wide Importers (WWI) is looking to formalize their sales process and
address the backlog of untouched leads imported by the marketing team from trade
shows and campaigns. You are a sales analyst for the Dynamics 365 Sales
implementation at World Wide Importers and have been asked to assess and update
lead records so the executive team can work from an accurate pipeline report in
the upcoming leadership meeting. In this lab, you will update lead records and
qualify, disqualify and reactivate lead records.

**Important Note:** This lab will provide you with an actual Dynamics 365 tenant
and licenses for the Power Platform applications you will be using in this
course. You will only be provided with one tenant for the practice labs in this
course. The settings and actions you take within this tenant do not roll-back or
reset, whereas the virtual machine you are provided with does reset each time
you close the lab session. Please be aware that Dynamics 365 is evolving all the time. The
instructions in this document may be different from what you experience in your
actual Dynamics 365 tenant. It is also possible to experience a delay of several
minutes before the virtual machine has network connectivity to begin the labs.

Exercise 1 – Manage Customers
-----------------------------

### Task 1 – Creating Leads

In this task, you will create three leads, one without company information and
two with company information.

1.  Go to your **Dynamics 365 Sales Hub** application.

2. Navigate to the left menu and explore the options available.

3. Select **Leads** from the **Sales** section of the left menu.

4.  Click **+ New**.

5.  Enter **[my prefix] Lead Without Company** for **Topic**, **Jane** for **First Name**,
    **Doe** for **Last Name**, and click **Save**.

6.  Click **+ New** again.

7.  Enter **[my prefix] Lead with Company** for **Title**, **Jon** for **First Name, Doe**
    for **Last Name**, **Doe Inc.** for **Company**, and click **Save**.

8.  Click **+ New** one more time.

9.  Enter **[my prefix] Another Lead** for **Title**, **Jack** for **First Name**, **Smith** for
    **Last Name,** **Test Inc**. for **Company**, and click **Save**.

Exercise 2 – Lead Qualifications
--------------------------------

In this exercise, you will qualify/disqualify leads and see what records will be
created when a lead goes through the qualification process.

### Task 1 – Qualify Lead Without Company Information 

1.  Go to your **Sales Hub** application.

2.  Select **Leads**.

3.  Locate **Lead Without Company** and select it.

4.  Click **Qualify** from the top menu.

5.  The lead will be **Qualified**. Select **Opportunities** from the left menu to see all qualified leads. Click on the lead you just qualified. 

6.  Locate the **Contact** field. You find that **Jane Doe** is now a
    **Contact** record.

7.  Locate the **Account** field. The field will be empty.

8. Click **Save.**

### Task 2 – Qualify Lead with Company

1.  Go to your **Sales Hub** application.

2.  Select **Leads**.

3.  Locate **Lead with Company** and open it.

4.  Click **Qualify** from the top menu.

5.  The lead will be **Qualified**, and you will be taken to a new Opportunity
    record created from the qualified **Lead**.

6.  Locate the **Contact** field. You find that **Jon Doe** is now a **Contact**
    record.

7.  Locate the **Account** field. You will find that **Doe Inc.** is now an
    **Account** record.

### Task 3 – Disqualify Lead

1.  Go to your **Sales Hub** application.

2.  Select **Leads**.

3.  Locate **Another Lead** and open it.

4.  Click **Disqualify** and select **No Longer Interested**.

5.  The Lead will be Disqualified, the status will change to No Longer
    Interested, and the record will become Read Only.

### Task 4 – Reactivate Lead

1.  Go to your **Sales Hub**,application.

2.  Click on the **Site Map** button and select **Leads**.

3.  The Lead you disqualified is no longer in the **My Open Leads** view. Change
    the View to **Closed Leads**.

4.  Locate **Another Lead** and open it. (Ensure the lead has your prefix.)

5.  Click **Reactivate Lead**.

6.  The Lead will be reactivated, the status will change to New, and the record
    will become editable.
