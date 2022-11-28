---
lab:
    title: 'Lab 5.1: Configure a dashboard'
    module: 'Module 5: Analyze Dynamics 365 Sales data'
---


Module 5: Analyze Dynamics 365 Sales data
==============================

## Practice Lab 5.1: Configure a dashboard 

Scenario
--------

Sales managers would like to more effectively monitor their sales team's success, especially around closed opportunities. One sales manager requests a personal dashboard where they can see an overview of recently closed opportunities and their sellers' actions against them. They'd like this dashboard to show up as the default dashboard when they open the Dashboards section of the application.

## Task 1 - Create a dashboard

1. Make sure you are in the **Sales** section of the application, if you are not already. Use the bottom-left dropdown menu to select **Sales** if you need to switch.

1. Select **Dashboards** from the left menu.

1. By default, the Sales Activity Social dashboard will appear. Feel free to explore the various components. Additionally, you can use the carrot next to the title of the dashboard to explore other system dashboards.

1. When you're ready to create your own dashboard, select **New**, and then select **Dynamics 365 Dashboard.**

1. Explore the various dashboard layouts. Today we will be creating a 2-Column Regular Dashboard. When you are ready, select it from the list and select **Create.**

## Task 2 - Add components

1. The dashboard designer will open in a new window. (If your new dashboard does not open in a new window, make sure your pop-up blocker is disabled.) The designer may take a minute to load.

1. In the **Name** text box, type "[my prefix] Sales Manager Dashboard".

1. Let's add a component to the upper left section. Sales managers are requesting an easy way to see the amount of won versus lost revenue from opportunities. They'd like this information in a graphical view. To accomplish this, we will add a chart by clicking the small bar graph icon in the middle of the upper left section.

1. Select the following details for your chart:
	- Record Type: Opportunity
	- View: Closed Opportunities
	- Chart: Deals Won vs. Deals Lost
	- Click **Add.**

1. Your chart will appear in the upper left section.

1. Next, let's add a component to the upper right section. Sales managers are requesting a way to easily view the recently closed opportunities so that they can check in with sellers on lessons learned. They would like the view to include both won and lost opportunities, but only opportunities closed in the current fiscal year. Select the icon that looks like a bulleted list in the middle of the upper right section.

1. Select the following details for your list:
	- Record Type: Opportunities
	- View: Closed Opportunities in Current Fiscal Year
	- Click **Add.**

## Task 3 - Save and edit your dashboard

1. Click **Save.** Your window will close and you will return to your Dashboards area, where your dashboard will be displayed.

1. Click **Set as default** from the top menu. This dashboard will now be your default dashboard when you navigate to the Dashboards section.

1. Click **Edit** from the top menu. You will return to the dashboard designer in another new window. Add two more components beneath your chart. The components you select should solve the following business requirements requested by sales managers.
	- Sales managers would like to get a sense of how individual sellers are doing based on their closed opportunity revenue. They would like a chart that shows seller names and their total revenue from closed opportunities.
	- Sales managers would like to monitor the day-to-day tasks of the sellers on their team. They would like to see a list that shows their sales teams' activities.
