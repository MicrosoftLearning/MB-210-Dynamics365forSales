---
lab:
    title: 'Lab: Manage product catalog'
    module: 'Module 3: From Quote to Orders'
---

Module 3: From Quote to Orders
==============================

## Practice Lab 1 – Manage product catalog

Scenario
--------

World Wide Importers (WWI) is looking to standardize their pricing structure and
allow for easier creation of quotes, orders, and invoices with accurate pricing
and product details. As a functional consultant on the Dynamics 365 for Sales
implementation, you have been asked to configure the product catalog. In this
lab, you will create a unit group, a price list, a discount list, and products.

**Important Note:** This lab will provide you with an actual Dynamics 365 tenant
and licenses for the Power Platform applications you will be using in this
course. You will only be provided with one tenant for the practice labs in this
course. The settings and actions you take within this tenant do not roll-back or
reset, whereas the virtual machine you are provided with does reset each time
you close the lab session. Please be aware that Dynamics 365 is evolving all the time. The
instructions in this document may be different from what you experience in your
actual Dynamics 365 tenant. It is also possible to experience a delay of several
minutes before the virtual machine has network connectivity to begin the labs.

Exercise 1 - Acquire Tenant Information and Connect
---------------------------------------------------

Note: If you have already completed a practice recently, the virtual machine
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

Exercise 2 – Product Catalog
----------------------------

### Task 1 – Create Unit Group

In this task, you will create unit groups for the speakers.

1.  Go to your **Dynamics 365 Sales Hub** application.

2.  Click on the **Site Map** button and click on the **…. More Options**
    button.

3.  Select **App Settings**.

4.  From the **Product Catalog** group, select **Unit Groups.**

5.  Click **+ New**.

6.  Enter **Speakers** for **Name**, enter **Each** for **Primary Unit**, and
    click **OK**.

7.  Click **Related** and select **Units**.

8.  You will find that you only have the default unit **Each** now; you will add
    three more units. Click **+ Add New Unit**.

9.  Enter **Speaker** for **Name**, **1** for **Quantity**, select **Each** for
    **Base Unit**, and click **Save & Create New**.

10. Enter **Pair** for **Name**, **2** for **Quantity**, select **Speaker** for
    **Base Unit** and click **Save & Create New**.

11. Enter **Set** for **Name**, **2** for **Quantity**, select **Pair** for
    **Base Unit** and click **Save**.

12. You will now have four unit-groups in the list.

### Task 2 – Create Discount List

In this task, you will create a Discount List for people that buy 3 or 4
speakers, the 3rd speaker will get 15% discount and 4 to 50 speakers will get
25% discount.

1.  From the **Product Catalog** group, select **Discount Lists.**

2.  Click **+ New**.

3.  Enter **Quantity Discount** for **Name**, select **Percent** for **Type**,
    and click **Save**.

4.  Click **Related** and select **Discounts**.

5.  Click **+ Add New Discount**.

6.  Make sure **Quantity Discount** is select for **Discount Type**, enter **2**
    for **Begin Quantity**, **3** for **End Quantity**, **15** for
    **Percentage** and click **Save**.

7.  Click **+ New** again.

8.  Select **Quantity Discount** for **Discount Type**, enter **4** for **Begin
    Quantity**, **50** for **End Quantity**, enter **25** for **Percentage**,
    and click **Save**.

### Task 3 – Create Price List

In this task, you will create a price list for the speakers.

1.  From the **Product Catalog** group, select **Price Lists.**

2.  Click **+ New**.

3.  Enter **Top D. Electronic** for **Name**, select **US Dollar** for
    **Currency**, and click **Save**.

### Task 4 – Create Products

In this task, you will create products.

1.  Click on the **Site Map** button and click on the **…. More Options**
    button.

2.  Select **Sales**.

3.  From the **Collateral** group, select **Products**.

4.  Click **Add Product.**

5.  Enter **Top D. HiFi** for **Name**, enter **1234** for **Product ID**,
    select **Speakers** for **Unit Group**, select **Speaker** for **Default
    Unit**, enter **2** for **Decimals Supported**, select **Products** for
    **Subject**, and click **Save**.

6.  Select the **Additional Details** tab.

7.  Click **Add New Price List Item**.

8.  Select **Top D. Electronic** for **Price List**, select **Quantity
    Discount** for **Discount List**, select **Whole** for **Quantity Selling
    Option**, and select the **Pricing Information** tab.

9.  Enter **150** for Amount and click **Save and Close**.

10. Click **Publish**.

11. Confirm the publishing.

12. Click on the **Site Map** button and select **Products**.

13. Click **Add Product**.

14. Enter **DX Power Supply** for **Name**, enter **4321** for **Product
    Number**, select **Default Unit** for **Unit Group**, select **Primary
    Unit** for **Default Unit**, enter **2** for **Decimals Supported**, and
    click **Save**.

15. Select the **Additional Details** tab.

16. Click **Add New Price List Item**.

17. Select **Top D. Electronic** for **Price List**, select **Whole** for
    **Quantity Selling Option**, and select the **Pricing Information** tab.

18. Enter **120** for Amount and click **Save and Close**.

19. Click **Publish**.

20. Confirm the publishing.

21. Click on the **Site Map** button and select **Products**.

22. Click **Add Product**.

23. Enter **Top D. Comm System** for **Name**, enter **7894** for **Product
    ID**, select **Default Unit** for **Unit Group**, select **Primary Unit**
    for **Default Unit**, enter **2** for **Decimals Supported**, and click
    **Save**.

24. Select the **Additional Details** tab.

25. Click **Add New Price List Item**.

26. Select **Top D. Electronic** for **Price List**, select **Whole** for
    **Quantity Selling Option**, and select the **Pricing Information** tab.

27. Enter **2500** for Amount and click **Save and Close**.

28. Click **Publish**.

29. Confirm the publishing.

30. Click on the **Site Map** button and select **Products**.

31. The products you created should show up on the All Products, Families &
    Bundles view. the products catalog.
