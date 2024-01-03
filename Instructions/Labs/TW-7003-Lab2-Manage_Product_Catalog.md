TW-7003: Optimize the Sales Process with Dynamics 365 Sales
==============================

## Lab 2: Manage product catalog

Scenario
--------

World Wide Importers (WWI) is looking to standardize their pricing structure and
allow for easier creation of quotes, orders, and invoices with accurate pricing
and product details. As a functional consultant on the Dynamics 365 for Sales
implementation, you have been asked to configure the product catalog. In this
lab, you will create a unit group, a price list, a discount list, and products.

**Important Note:** This lab will provide you with an actual Dynamics 365 tenant and licenses for the Power Platform applications you will be using in this course. You will only be provided with one tenant for the practice labs in this course. The settings and actions you take within this tenant do not roll-back or reset, whereas the virtual machine you are provided with does reset each time you close the lab session. Please be aware that Dynamics 365 is evolving all the time. The instructions in this document may be different from what you experience in your actual Dynamics 365 tenant. It is also possible to experience a delay of several minutes before the virtual machine has network connectivity to begin the labs.

Exercise 1 – Product Catalog
----------------------------

### Task 1 – Create Unit Group

In this task, you will create unit groups for the speakers.

1.  Go to your **Dynamics 365 Sales Hub** application.

2.  Click **Change area**, by default **Sales** will be displayed in the bottom of the left menu.

3.  Select **App Settings**.

4.  Select **Unit Groups** from the **Product Catalog** section of the left menu.

5.  Click **+ New**.

6.  Enter **[my prefix] Speakers** for **Name**, enter **Each** for **Primary Unit**, and
    click **OK**.

7.  Click **Related** and select **Units**.

8.  You will find that you only have the default unit **Each** now; you will add
    three more units. Click **+ New Unit**.

9.  Enter **Speaker** for **Name**, **1** for **Quantity**, select **Each** for
    **Base Unit**, and click **Save & Create New** by selecting the &#709; dropdown icon to the right of the **Save & Close** button.

10. Enter **Pair** for **Name**, **2** for **Quantity**, select **Speaker** for
    **Base Unit** and click **Save & Create New**.

11. Enter **Set** for **Name**, **2** for **Quantity**, select **Pair** for
    **Base Unit** and click **Save and Close**.

12. You will now have four unit groups in the list.

### Task 2 – Create Discount List

In this task, you will create a Discount List for people that buy 3 or 4
speakers. The 3rd speaker will get 15% discount and 4 to 50 speakers will get a
25% discount.

1.  Select **Discount Lists** from the **Product Catalog** section of the left menu.

2.  Click **+ New**.

3.  Enter **[my prefix] Quantity Discount** for **Name**, select **Percentage** for **Type**,
    and click **Save**.

4.  Click **Related** and select **Discounts**.

5.  Click **+ New Discount**.

6.  Make sure **[my prefix] Quantity Discount** is selected for **Discount Type**, enter **2**
    for **Begin Quantity**, **3** for **End Quantity**, **15** for
    **Percentage** and click **Save**.

7.  Click **+ New** again.

8.  Select **[my prefix] Quantity Discount** for **Discount Type** by starting to enter in your prefix. Then enter **4** for **Begin
    Quantity**, **50** for **End Quantity**, enter **25** for **Percentage**,
    and click **Save**.

### Task 3 – Create Price List

In this task, you will create a price list for the speakers.

1.  Select **Price Lists** from the **Product Catalog** section of the left menu. 

2.  Click **+ New**.

3.  Enter **[my prefix] Top D. Electronic** for **Name**, select **US Dollar** for
    **Currency**, and click **Save**.

### Task 4 – Create Products

In this task, you will create products.

1.  Click on the **App Settings** change area.

2.  Select **Sales**.

3.  Select **Products** from the **Collateral** section of the left menu.

4.  Click **Add Product.**

5.  Enter **[my prefix] Top D. HiFi** for **Name**, enter **[myprefix]1234** for **Product ID**,
    select **[my prefix] Speakers** for **Unit Group** (you can easily find it by typing in your prefix), select **Speaker** for **Default
    Unit**, enter **2** for **Decimals Supported**, and click **Save**.

6.  Select the **Additional Details** tab.

7.  Click the vertical ellipsis on the top right of the **Price List Items** section. Click **+ New Price List Item**.

8.  Select **[my prefix] Top D. Electronic** for **Price List**, select **[my prefix] Quantity
    Discount** for **Discount List**, select **Whole** for **Quantity Selling
    Option**, and select the **Pricing Information** tab.

9.  Enter **150** for Amount and select **Save & Close**.

10. If Auto publish is enabled, skip this step. Otherwise, select **Publish** and **Confirm** to publish the Product.

11. In the left menu, select **Products** in the Collateral group.

12. Click **Add Product**.

13. Enter **[my prefix] DX Power Supply** for **Name**, enter **[myprefix]4321** for **Product
    ID**, select **Default Unit** for **Unit Group**, select **Primary
    Unit** for **Default Unit**, enter **2** for **Decimals Supported**, and
    click **Save**.

14. Select the **Additional Details** tab.

15. Click the vertical ellipsis on the top right of the **Price List Items** section. Click **+ New Price List Item**.

16. Select **[my prefix] Top D. Electronic** for **Price List**, select **Whole** for
    **Quantity Selling Option**, and select the **Pricing Information** tab.

17. Enter **120** for Amount and select **Save & Close**.

18. If **Auto publish** is enabled; skip this step. Otherwise, select **Publish** and **Confirm** to publish the Product.

21. Select **Products** from the left menu.

22. Click **Add Product**.

23. Enter **[my prefix] Top D. Comm System** for **Name**, enter **[myprefix]7894** for **Product
    ID**, select **Default Unit** for **Unit Group**, select **Primary Unit**
    for **Default Unit**, enter **2** for **Decimals Supported**, and click
    **Save**.

24. Select the **Additional Details** tab.

25. Click the vertical ellipsis on the top right of the **Price List Items** section. Click **+ New Price List Item**.

26. Select **[my prefix] Top D. Electronic** for **Price List**, select **Whole** for
    **Quantity Selling Option**, and select the **Pricing Information** tab.

27. Enter **2500** for Amount and select **Save & Close**.

28. If **Auto publish** is enabled; skip this step. Otherwise, select **Publish** and **Confirm** to publish the Product.

30. From the left menu, select **Products**.

31. The products you created should show up on the **All Products, Families & Bundles** view. You can switch to this view by selecting the **&#709; dropdown icon** next to the default view title. You can use the **Filter by keyword** box to search for your prefix to find your products.
