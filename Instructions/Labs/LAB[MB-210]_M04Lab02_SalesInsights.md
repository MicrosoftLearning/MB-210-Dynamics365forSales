---
lab:
    title: 'Lab: Sales Insights'
    module: 'Module 4: Sales Analytics and Insights'
---

Module 4: Sales Analytics and Insights
==================================

## Practice Lab – Sales Insights

Scenario
--------

One of the primary selling points of Dynamics 365 Sales to World Wide
Importers (WWI) was the integration of Artificial Intelligence (AI) to make
sales data immediately actionable for their sales users. You are a functional
consultant configuring Dynamics 365 Sales for World Wide Importers. You have
been tasked with enabling out of the box Insights functionality so that users can use
tools such as the relationship assistant, productivity cards and email
intelligence. In this lab, you will enable Sales Insights and explore the settings.

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
might pickup where you left off and you will not need to login again.  In that
case you can skip ahead to exercise two and resume.

### Task 1 – Connect to the Power platform administration portal

1.  On Virtual machine MB200-Dynamics_Lab, sign in as Admin with the password
    Pa55w.rd if you are not already logged in.

2.  Outside the VM in the online lab interface click Files and choose D365
    Credentials. This will allocate an Office 365 tenant for you to use in these
    labs.  It will display the admin email and password for your tenant.  You
    should copy this information to notepad or similar for your reference.

3.  In MB200-Dynamics_Lab launch Microsoft Edge from the taskbar. By default,
    the browser opens Office 365. Use the O365 credentials you just acquired in
    the previous step to login.

4.  Navigate in the browser to the Power platform admin portal at
    [https://admin.Powerplatform.microsoft.com](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fadmin.Powerplatform.microsoft.com&data=02%7C01%7Cv-juya%40microsoft.com%7C4be5a28c6f1e41eefee808d687ae2dc7%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636845580068684293&sdata=cLrD%2FhTDb5sRbajtFR9RrztfyTDCo0xGS4k8FSxTaIc%3D&reserved=0)

Exercise 2 – Sales Intelligence
-------------------------------

### Task 1 – Review Personal Configuration

1.  Go to your **Dynamics 365 Sales Hub** application.

2.  Click on the **Site Map** button and click on the **Sales Insights settings**
    button.

3.  Examine what is available by default. You should see Assistant, Auto capture and Email engagement available.

### Task 2 – Enable and explore Sales Insights 

In this task, you will enable Relationship Assistant, Email Engagement, and Auto
Capture.

1.  In **Sales Insights settings**, confirm that you are on the **Overview tab.**

2.  Scroll down to the **Terms of service** section and click the **I agree** button.

3.  Assistant and Auto capture should now have **Manage >** links next to their tabs.

4. Click **Grant permissons** next to Email Engagement and accept the permissions in the dialog box.
**Note:** Additional permissions may be required to enable Email Engagement. Depending on your virtual machine, you may not be able to set up these permissions. If this is the case in your virtual machine, skip 

5.  Click on the **Manage** button next to Assistant.

6.  You will be taken to the **Relationship Assistant** tab. Review and explore the available cards.

7. Select the **Recent Meeting** card and explore the card details. Toggle the card to **Off.** This card is now disabled.

8. Click **Save.**

9. Return to the list of available cards. **Recent Meeting** should no longer be visible at the top of the list.

10. Return to the Overview tab.

11. On the Overview tab, click **Manage >** next to Auto capture.

12. Confirm Auto capture is enabled via the toggle.

13. Return to the Overview tab.

14. On the Overview tab, click **Manage >** next to Email engagement.

15. Confirm Email engagement is enabled via the toggle.
