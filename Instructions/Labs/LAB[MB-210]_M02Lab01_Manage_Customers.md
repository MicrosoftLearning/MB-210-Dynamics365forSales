---
lab:
    title: 'Lab: Manage Customers'
    module: 'Module 2: From Lead to Opportunity'
---


Module 2: From Lead to Opportunity
==================================

## Practice Lab 2 – Manage customers

Scenario
--------

World Wide Importers (WWI) is looking to formalize their sales process and
address the backlog of untouched leads imported by the marketing team from trade
shows and campaigns. You are a sales analyst for the Dynamics 365 for Sales
implementation at World Wide Importers and have been asked to assess and update
lead records so the executive team can work from an accurate pipeline report in
the upcoming leadership meeting. In this lab, you will update lead records and
qualify, disqualify and reactivate leads records.

**Important Note:** This lab will provide you with an actual Office 365 tenant
and licenses for the Power platform applications you will be using in this
course. You will only be provided with one tenant for the practice labs in this
course. The settings and actions you take within this tenant do not roll-back or
reset. Whereas the virtual machine you are provided with does reset each time
you close the lab session. What’s more, Office 365 is evolving all the time. The
instructions in this document may be different from what you experience in your
actual Office 365 tenant. It is also possible to experience a delay of several
minutes before the virtual machine has network connectivity to begin the labs.

Exercise 1 - Acquire Tenant Information and Connect
---------------------------------------------------

**Note:** If you have already completed a practice recently, the virtual machine
might pickup where you left off and you will not need to login again.  In that
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

Exercise 2 – Manage Customers
-----------------------------

### Task 1 – Creating Leads

In this task, you will create three leads, one without company information and
two with company information.

1.  Go to your **Dynamics 365 Sales Application**.

2.  Click **Switch to Another App** button and select **Sales Hub**.

3.  Click on the **Site Map** button and select **Leads**.

4.  Click **+ New**.

5.  Enter **Lead Without Company** for **Title**, **Jane** for **First Name,
    Doe** for **Last Name**, and click **Save**.

6.  Click **+ New** again.

7.  Enter **Lead with Company** for **Title**, **Jon** for **First Name, Doe**
    for **Last Name**, **Doe Inc.** for **Company**, and click **Save**.

8.  Click **+ New** one more time.

9.  Enter **Another Lead** for **Title**, **Jack** for **First Name, Smith** for
    **Last Name, Test Inc**. for **Company**, and click **Save**.

Exercise 3 – Lead Qualifications
--------------------------------

In this exercise, you will qualify/disqualify leads and see what records will be
created when a lead goes through the qualification process.

### Task 1 – Qualify Lead Without Company Information 

1.  Go to your **Sales Hub**, application.

2.  Click on the **Site Map** button and select **Leads**.

3.  Locate **Lead Without Company** and open it.

4.  Click **Qualify**.

5.  The lead will be **Qualified**, and you will be taken to a new Opportunity
    record created from the qualified **Lead**.

6.  Locate the **Contact** field, you find that **Jane Doe** is now a
    **Contact** record.

7.  Locate the **Account** field, the Company field will be empty.

### Task 2 – Qualify Lead with Company

1.  Go to your **Sales Hub**, application.

2.  Click on the **Site Map** button and select **Leads**.

3.  Locate **Lead with Company** and open it.

4.  Click **Qualify**.

5.  The lead will be **Qualified**, and you will be taken to a new Opportunity
    record created from the qualified **Lead**.

6.  Locate the **Contact** field, you find that **Jon Doe** is now a **Contact**
    record.

7.  Locate the **Account** field, you will find that **Doe Inc.** is now an
    **Account** record.

### Task 3 – Disqualify Lead

1.  Go to your **Sales Hub**, application.

2.  Click on the **Site Map** button and select **Leads**.

3.  Locate **Another Lead** and open it.

4.  Click **Disqualify** and select **No Longer Interested**.

5.  The Lead will be Disqualified, the status will change to No Longer
    Interested, and the record will become Read Only.

### Task 4 – Reactivate Lead

1.  Go to your **Sales Hub**, application.

2.  Click on the **Site Map** button and select **Leads**.

3.  The Lead you disqualified is no longer in the **Open Leads** view. Change
    the View to **Closed Leads**.

4.  Locate **Another Lead** and open it.

5.  Click **Reactivate Lead**.

6.  The Lead will be reactivated, the status will change to New, and the record
    will become editable.
