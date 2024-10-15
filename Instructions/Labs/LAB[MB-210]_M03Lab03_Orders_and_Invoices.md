---
lab:
    title: 'Lab 3.3: Orders and invoices'
    module: 'Module 3: Manage orders and product catalog with Dynamics 365'
---


Module 3: Manage orders and product catalog with Dynamics 365
==============================

## Practice Lab 3.3 – Orders and invoices

Scenario
--------

As a sales analyst for the Dynamics 365 for Sales implementation at World Wide
Importers, you need to test the newly configured product catalog enhancements to
the order and invoice processes. In this lab, you will create an order from a
quote and create an invoice from that order.

**Important Note:** This lab will provide you with an actual Dynamics 365 tenant and licenses for the Power Platform applications you will be using in this course. You will only be provided with one tenant for the practice labs in this course. The settings and actions you take within this tenant do not roll-back or reset, whereas the virtual machine you are provided with does reset each time you close the lab session. Please be aware that Dynamics 365 is evolving all the time. The instructions in this document may be different from what you experience in your actual Dynamics 365 tenant. It is also possible to experience a delay of several minutes before the virtual machine has network connectivity to begin the labs.

Exercise 1 – Orders and Invoices
--------------------------------

### Task 1 – Create Order

In this task, you will create an Orders from a Quote.

1.  Go to your **Dynamics 365 Sales Hub** application.

2.  In the left menu, select **Quotes**.

3.  Open the **Quote** you created titled **Interested in Top D. System**.

    > **Hint:** Change the view to **My Quotes** to retrieve the quotes created.

4.  Select **Create Order**.

5.  Leave everything as default and click **OK**.

6.  The **Order** form will open. You can edit the **Order** information.

7.  Select the vertical ellipsis button (⋮) at the end of the command bar. Select **Word Template** and then select
    **Order Summary**.

8.  Open the generated Word document and review the **Order**. Close the Order
    Summary.

9.  Select the vertical ellipsis button (⋮) at the end of the command bar and select **Fulfill Order**.

10. Select **Fulfill**. The record will become read-only. Do not navigate away from this page.


### Task 2 – Create Invoice

In this task, you will create an Invoice.

1.  Make sure you are still in the **Order** form.

2.  Select **Create Invoice** from the command bar.

3.  The **Invoice** form will open.

4.  Select the vertical ellipsis button (⋮) at the end of the command bar. Select **Word Template** and then select
    **Invoice Summary**.

5.  Open the generated Word doc and review the **Invoice**. Close the Invoice
    Summary.

6.  We will assume the Customer paid in full. Select **Invoice Paid**.

7.  Select **OK** to mark the Invoice as Complete.

