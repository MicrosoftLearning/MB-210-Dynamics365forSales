---
lab:
    title: 'Lab 3.2: Build quotes'
    module: 'Module 3: Manage orders and product catalog with Dynamics 365'
---


Module 3: Manage orders and product catalog with Dynamics 365
==============================

## Practice Lab 3.2 – Build quotes

Scenario
--------

As a sales analyst for the Dynamics 365 Sales implementation at World Wide
Importers, you need to test the newly configured product catalog enhancements to
the quoting process. In this lab, you will add product line items to an
opportunity and create a quote from that opportunity.

**Important Note:** This lab will provide you with an actual Dynamics 365 tenant and licenses for the Power Platform applications you will be using in this course. You will only be provided with one tenant for the practice labs in this course. The settings and actions you take within this tenant do not roll-back or reset, whereas the virtual machine you are provided with does reset each time you close the lab session. Please be aware that Dynamics 365 is evolving all the time. The instructions in this document may be different from what you experience in your actual Dynamics 365 tenant. It is also possible to experience a delay of several minutes before the virtual machine has network connectivity to begin the labs.


Exercise 1 – Create a Quote
-------------------------

### Task 1 – Add Products Line Items

In this task, you will create an Opportunity and add Products Line Items.

1.  Go to your **Dynamics 365 Sales Hub** application.

2.  From the left menu, in the **Sales** group, select **Opportunities**.

3.  Click **+ New**.

4.  Enter **[my prefix] Interested in Top D. System** for **Topic**, select **Jon Doe** for
    **Contact**, select **Doe Inc.** for **Account** and select **Save**.

5.  Select the **Products** tab. 

6.  You must select a **Price List** before you can add Opportunity Products.
    Select **[my prefix] Top D. Electronics** for **Price List**.

7.  Select **System Calculated** for **Revenue**.

8.  Above the subgrid, click **+ Add products**.

9.  From the **All products** list, find **[my prefix] DX Power Supply**, enter **2** for
    **Quantity**, select **Add**.

10. Find **[my prefix] Top D. Comm System** in the list of products, enter **1** for
    **Quantity** and select **Add**.

11. Find **[my prefix] Top D. HiFi** in the list of products, enter **1** for
    **Quantity** and select **Add**.

12. You will see three products are **Selected**. Select **Save to opportunity**.

13. Double click on the **[my prefix] Top D. HiFi** product.

14. Locate the **Volume Discount** field. You will find that there is no
    discount for buying one Speaker. 

15. Change the **Quantity** to **4** and click out of the field. The Discount will now kick in and the
    Volume Discount field will show the discounted value.

16. Select **Save & Close**.


### Task 2 – Create Quote

In this task, you will create a Quote from the Opportunity you created in Task

1.  Go to your **Dynamics 365 Sales Hub** application.

2.  Open the Opportunity you created in the previous task. It will be called **[my prefix] Interested in Top D. System.**

3.  Select the **Quotes** tab.

4.  Above the subgrid, Click **+ New Quote**.

5.  The **Quote** form will open, and relevant information will be copied from the
    Opportunity.

6.  On the **[my prefix] Interested in Top D. System.** Quote page. Examine the **Products** sub-grid and make sure products and their
    quantities look as you expected. You can change the quantities and discount
    the price of each line item.

7.  Click **Activate Quote**.

8.  Click **Export to PDF** located on the command bar and select **Print Quote for Customer**. Click **Download.**

9.  **Open** the generated document and see what the Quote looks like.

10. **Close** the PDF.

11. Close the **Export to PDF** window.

