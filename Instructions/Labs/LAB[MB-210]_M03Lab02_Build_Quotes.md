---
lab:
    title: 'Lab: Build quotes'
    module: 'Module 3: From Quote to Orders'
---


Module 3: From Quote to Orders
==============================

## Practice Lab 2 – Build quotes

Scenario
--------

As a sales analyst for the Dynamics 365 for Sales implementation at World Wide
Importers, you need to test the newly configured product catalog enhancements to
the quoting process. In this lab, you will add product line items to an
opportunity and create a quote from that opportunity.

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

Exercise 2 – Create Quote
-------------------------

### Task 1 – Add Products Line Items

In this task, you will create an Opportunity and add Products Line Items.

1.  Go to your **Dynamics 365 Sales Hub** application.

2.  Click on the **Site Map** button and select **Opportunities**.

3.  Click **+ New**.

4.  Enter **Interested in Top D. System** for **Topic**, select **Jon Doe** for
    **Contact**, select **Doe Inc.** for **Account** and click **Save**.

5.  Select the **Product Line Items** tab.

6.  You must select a **Price List** before you can add Opportunity Products.
    **Select Top D. Electronics** for **Price List**.

7.  Select **System Calculated** for **Revenue**.

8.  Go to the **Opportunity Products** sub-grid and click **+ New Opportunity
    Product**.

9.  Select **DX Power Supply** for **Existing Product**, enter **2** for
    **Quantity**, and click **Save & Create New**.

10. Select **Top D. Comm System** for **Existing Product**, enter **1** for
    **Quantity** and click **Save & Create New**.

11. Select **Top D. HiFi** for **Existing Product**, enter **1** for
    **Quantity** and click **Save**.

12. You will have three products in the sub-grid. Double click on the **Top D.
    HiFi** product.

13. Locate the **Volume Discount** field. You will find that there is no
    discount for buying one Speaker.

14. Change the **Quantity** to **4**. The Discount will now kick in and the
    Volume Discount field will show the discounted value.

### Task 2 – Create Quote

In this task, you will create a Quote from the Opportunity you created in Task
1.

1.  Go to your **Dynamics 365 Sales Hub** application.

2.  Open the Opportunity you created in task 1 **Interested in Top D. System**

3.  Select the **Quotes** tab.

4.  Click **+ Add New Quote**.

5.  The Quote form will open, and relevant information will be copied from the
    Opportunity.

6.  Examine the **Quote Products** sub-grid and make sure products and their
    quantities look as you expected. You can change the Quantities and discount
    the price of each line item.

7.  Scroll down to the **Details** section. You can discount the total amount
    and add freight amount.

8.  Go to the **Address** section.

9.  Enter **1 Microsoft Way** for **Bill To Street 1**, **Redmond** for **Bill
    To City**, **WA** for **Bill To State**, **98052** for **Bill To Zip**.

10. Go to header and select today’s date for **Effective From**, select five
    days for today for **Effective To** and click **Save**.

11. Click **Activate Quote**.

12. Click **Word Template** locate on the command bar and select **Print Quote
    for Customer**

13. Open the generated document and see what the Quote looks like.

14. **Active Quotes** are read only, you must **Revise** active **Quotes**
    before you can edit them. Click **Revise**.

15. Change the **Effective To** date to **10** days from today.

16. Click **Save**.

17. Click **Activate Quote** again.

18. Go to the **Sales Information** section and click on the **Opportunity**.
    This action will take you back to the Opportunity.

19. Select the **Quotes** tab.

20. Click on the **Refresh** button of the **Quotes** grid.

21. You will now have two Quotes. When you revise a Quote, the system will close
    the initial Quote and create a new Quote for it.
