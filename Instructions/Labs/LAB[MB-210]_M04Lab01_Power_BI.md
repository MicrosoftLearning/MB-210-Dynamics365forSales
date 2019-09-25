---
lab:
    title: 'Lab: Power BI'
    module: 'Module 4: Sales Analytics and Insights'
---


Module 4: Sales Analytics and Insights
======================================

## Practice Lab 1 – Power BI

Scenario
--------

Dynamics 365 for Sales works well with Power BI to display Dynamics data in Power
BI. You are a sales analyst for the Dynamics 365 for Sales implementation at
World Wide Importers and have been asked to assess implementation of Power BI
with your sales data.

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

Exercise 2 – Power BI with Dynamics 365
---------------------------------------

### Task 1 – Enable Power BI

1.  Go to your **Dynamics 365 Sales** application. Select **Sales** not Sales
    Hub.

2.  Navigate to **Settings > Administration**.

3.  Select **System Settings**.

4.  Select the **Reporting** tab and set **Allow Power BI Embedding** to
    **Yes**.

5.  Click **OK**.

6.  Click **Switch to Another App** and select **Sales Hub.**

7.  Click on the **Site Map** button and select **Dashboards**.

8.  Click **New**. You will now have an option for creating **Power BI
    Dashboards**.

9.  Select **Power BI Dashboard**. You will get a message telling you to create
    power bi dashboard first.

10. Click **Cancel**.

11. Click **New** again and select **Dynamics 365 Dashboard**.

12. Select **2 Column Regular Dashboard** and click **Create**.

13. You should have an option for adding **Power BI Tile**.

14. Click **Add Power BI Tile**. You will get message telling you that you don’t
    have Power BI tiles or Dashboards.

15. Click **Cancel**.

16. Close the create dashboard window without saving it.

17. Click **Done**.

18. Do not close this browser window.

### Task 2 – Try Power BI Sample

1.  Start a new browser window and navigate to <https://powerbi.microsoft.com/>

2.  Click **Sign in**.

3.  Click **Sign in** again to sign in with existing account.

4.  Click **Start**.

5.  Click **Skip**.

6.  Go to the **More Ways to Create your Own Content** area and click
    **Samples**.

7.  Select **Customer Profitability Sample** and click **Connect.**

8.  **Power BI** will create a dashboard from the sample you selected.

9.  Click on the **Gross Margin** tile. The report will load. Return to the main
    dashboard.

10. Go to the **Total Revenue by Region** and select **North**.

11. The report will reflect your selection.

12. Go to the **Executive** visual and select **Carlos Grilo**.

13. The report will reflect your selection.

14. Go ahead and explore the sample report.

### Task 3 – Add Power BI Dashboard to Dynamics 365 

1.  Go back to your **Sales Hub** application.

2.  Click **New** and select **Power BI Dashboard**.

3.  You should see the **Customer Profitability Sample** dashboard. Select the
    **Customer Profitability Sample** dashboard and click **Save**.

4.  The **Power BI Dashboard** should load in your **Dynamics 365**.

5.  Click on the **Gross Margin %** tile. You will find that Power BI charts are
    not interactive.

6.  Click **Open Power BI Report.**

7.  The report should load. Go to **Total Revenue by Region** and select
    **North**. The report should be interactive.

### Task 4 – Mixed Power BI Tiles and Dynamics 365 

1.  Click on the **Site Map** button and select **Dashboards**.

2.  Click **New** and select **Dynamics 365 Dashboard**.

3.  Click **Add Power BI Tile**. You should now be able to select individual
    tiles form the sample dashboard.

4.  Select **Total Revenue** for **Tile** and Click **OK**.

5.  Click **Add Power BI Tile** again.

6.  Select **Gross Margin %** for **Tile** and Click **OK**.

7.  Click Insert **Chart**.

8.  Select **Opportunity** for **Record Type,** select **My Open Opportunities**
    for **View**, select **Sales Pipeline** for **Chart** and click **Add**.

9.  Select **Insert List**.

10. Select **Accounts** for **Record Type**, select **All Accounts** for
    **View** and click **Add**.

11. Enter **Mixed Dash** for **Name** and click **Save**.

12. Click **Close**.

13. The **Mixed Dash** should load.

### Task 5 – Build Dashboard

1.  Go back <https://powerbi.microsoft.com/>

2.  Click on the **Customer Profitability Sample** located in the
    **Workspace>Datasets** area of the navigation pane.

3.  Go to **Fields** pane and expand **Customers.**

4.  Select **City**. Map visualization will be added canvas.

5.  Click on the canvas and select **Name**. Make sure you don’t have the map
    selected. A table will be added to canvas.

6.  With the table still selected, select **City** and **State Code** from the
    Customers. Two columns will be added to the table.

7.  Click on the canvas, expand **Facts** and select **Revenue % Variance to
    Budget**. Clustered Column chart will be created.

8.  With the column chart still selected, click **Stacked Ares Chart**.

9.  With the **Stacked Area Chart** still selected, expand **Dates** and select
    **Month**.

10. With the **Stacked Area Chart** still selected, expand **Executives** and
    select **Executive**.

11. Click on the canvas, expand **Executives** and select **Executive**. A table
    will be added to the canvas.

12. With the new table selected **Slicer** visualization. The table will change
    to **Slicer**.

13. Click on the canvas, go to the **Visualizations** and select **Tree Map**.

14. Expand **Facts** and select **Total Revenue**.

15. With the **Three Map** still selected, expand **Business Units** and select
    **Division**.

16. With the **Three Map** still selected, drag the **Division** field and drop
    it under the **Values** label.

17. Resize and reposition the visualizations to your liking.

18. Click **Save**.

19. Enter **My Report** for **Name** and click **Save**.

20. Click **Pin Live Page**. You must Pin Live Page before you can see Power BI
    dashboards in Dynamics 365.

21. Select **New Dashboard,** enter **My Dash** for **Name**, and click **Pin
    Live**.

22. Hover over the **Stacked Area Chart** and click **Pin**.

23. Select **My Dash** and click **Pin**. You must pin before you can see
    individual Power BI tiles in Dynamics 365.

24. You may Pin the rest of tiles if you want to see them in Dynamics 365.

25. Go to the navigation pane and from the **Reports** section click **My
    Report**.

26. You report will load.

27. Go ahead and try to create Dynamics 365 Dashboard from the Power BI
    dashboard and tiles you created.
