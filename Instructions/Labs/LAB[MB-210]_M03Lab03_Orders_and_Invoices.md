---
lab:
    title: 'Lab: Orders and invoices'
    module: 'Module 3: From Quote to Orders'
---


Module 3: From Quote to Orders
==============================

## Practice Lab 3 – Orders and invoices

Scenario
--------

As a sales analyst for the Dynamics 365 for Sales implementation at World Wide
Importers, you need to test the newly configured product catalog enhancements to
the order and invoice processes. In this lab, you will create an order from a
quote and create an invoice from that order.

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

Exercise 2 – Orders and Invoices
--------------------------------

### Task 1 – Create Order

In this task, you will create an Orders from a Quote.

1.  Go to your **Dynamics 365 Sales Hub** application.

2.  Click on the **Site Map** button and select **Quotes**.

3.  Open the **Quote** you created **Interested in Top D. System**.

4.  Click **Create Order**.

5.  Leave everything as default and click **OK**.

6.  The **Order** form will open. You can edit the **Order** information.

7.  Click on the **Word Template** button located in the command bar and select
    **Order Summary**.

8.  Open the generated Word doc and review the **Order**. Close the Order
    Summary.

9.  Click **Fulfill Order**.

10. Click **Fulfill**. Do not navigate away from this page.

### Task 2 – Create Invoice

In this task, you will create an Invoice.

1.  Make sure you are still in the **Order** form.

2.  Click **Create Invoice**.

3.  The **Invoice** for will open.

4.  Click on the **Word Template** button located in the command bar and select
    **Invoice Summary**.

5.  Open the generated Word doc and review the **Invoice**. Close the Invoice
    Summary.

6.  We will assume the Customer paid in full. Click **Invoice Paid**.

7.  Select **Complete** and click **OK**.
