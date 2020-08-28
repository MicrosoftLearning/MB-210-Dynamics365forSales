---
demo:
    title: 'Demo: Customize the sales process'
    module: 'Module 2: From Lead to Opportunity'
---


Module 2: From Lead to Opportunity
==================================

## Instructor Demo – Customize the sales process

Scenario
--------

World Wide Importers (WWI) is looking to formalize their sales process to
increase revenue and the give leadership stronger forecasting abilities. You are
a functional consultant configuring Dynamics 365 for Sales for World Wide
Importers. In this lab, you will create a business process flow to guide the
sales process experience for users.

Exercise 1 – Customize Business Process Flow
--------------------------------------------

### Task 1 – Create Business Process Flow

In this task, you will create a new Business Process Flow from the Opportunity
Sales Process and then test the new BPF.

1.  Navigate to <https://make.powerapps.com>.

2.  Ensure that you are in the **Contoso** environment. 
- This demo will make configuration changes to the Dynamics 365 organization. Please ensure that this demo is only completed by an MCT.

3.  Select **Solutions** and click on the **Default Solution**.

4.  Locate the **Search** box in the top left corner of the page and click on
    the **All** drop-down.

5.  Select **Process.**

6.  Type **Opportunity** in the search box.

7.  Locate and open the **Opportunity Sales Process**.

8.  Click **Deactivate**.

9.  Confirm deactivation.

10. Click **Save As**.

11. A new browser window will open the copied Business Process Flow and the new
    process will be named **Opportunity Sales Process (Copy)**. Click on the
    **Show Details** button located next to the name.

12. Change the Process **Name** to **Opportunity Sales Process V2**.

13. Click **Save**.

14. Drag **Condition** from the **Components** tab and place it between the
    **Qualify** and **Develop** stages.

15. Select the **Condition**, go to the **Properties** tab, and enter **Check
    Budget** for **Display Name**.

16. Go to **Rule 1** and select **Budget Amount** for **Field**.

17. Select **Is Greater than or Equals to** for **Operator**.

18. Select **Value** for **Type**.

19. Enter **1000000** for **Value** and click **Apply**.

20. Click **Save**.

21. A new stage will be added to Business Process flow.

22. Select the new stage and select the **Properties** tab.

23. Enter **Thank You** for **Display Name** and click **Apply.**

24. Click the **Details** button of the **Thank You** stage.

25. Select the **New Step** inside the **Thank You** stage.

26. From the **Components** tab and select **Send Thank You Note** for **Data
    Field**.

27. Check the **Required** check box and click **Apply**.

28. Click **Save**.

29. Click **Activate**.

30. Confirm the activation.

31. Close the Business process Flow editor.

32. Close the Opportunity Sales Process window.

33. Click **Done**.

### Task 2 – Add Business Process Flow

In this task, you will remove the old business process flow from your Sales Hub
application and add the V2 business process flow.

1.  Navigate <https://web.powerapps.com/>

2.  Make sure you are **NOT** in **Default** environment.

3.  Select **Apps**.

4.  Select the **Sales Hub** application and click **Edit**.

5.  The application designer will open. Select the **Business Process Flow**
    tile.

6.  From the **Components** tab uncheck the **Opportunity Sales Process**
    checkbox and check the **Opportunity Sales Process V2** checkbox.

7.  Click **Save**.

8.  Click **Publish**.

9.  Close the application designer.

### Task 3 – Test Business Process Flow

1.  Navigate <https://web.powerapps.com/>

2.  Make sure you are **NOT** in **Default** environment.

3.  Select **Apps**.

4.  Click to open the **Sales Hub** application.

5.  Click **Site Map** and select **Opportunities**.

6.  Click **+ New**.

7.  Enter **Test Opportunity** for **Topic**.

8.  Select **Jane Doe** for **Contact**.

9.  Enter **900000** for **Budget Amount** and click **Save**.

10. Click Process and select Switch Process.

11. Select the **Opportunity Sales Process V2** process and click **OK**.

12. The Business Process Flow should have 4 stages, **Qualify**, **Develop**,
    **Propose**, and **Close**. The Thank You stage will not be part of the
    process if the Budget Amount is less than \$1,000,000.

13. Change the **Budget Amount** to 1000000.

14. The Business Process Flow should have 5 stages, **Qualify**, **Thank You**,
    **Develop**, **Propose**, and **Close**.

15. Click on the **Qualify** Stage.

16. Click **Next Stage**.

17. The process should move to the **Thank You** stage. Click **Next Stage**.

18. The process should not move to the next stage until the **Send Thank You**
    step is marked complete.

19. Check the **Mark Complete** checkbox and click **Next Stage**.

20. The process should now move to the **Develop** stage.
