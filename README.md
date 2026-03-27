Deploy to Production/Developer Edition Orgs :

<a href="https://githubsfdeploy.herokuapp.com?owner=findocklabs&repo=findock-healthcheck-fundraising&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

Deploy to Sandboxes Orgs :

<a href="https://githubsfdeploy-sandbox.herokuapp.com?owner=findocklabs&repo=findock-usage-reports&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

# FinDock Health Check Dashboards for Fundraising

A quick description of what this repo contains:
- Reports and a Dashboard to help monitor failed or Pending FinDock Processes that include Payment Schedules, Inbound Reports, Messages, Logs, Installments, Transaction Sets and Transactions
- A Report folder where all these Reports are placed
- A Dashboard Folder where the Dashboard is placed
- These reports and dashboards are built to work with FinDock used with the Non Profit Cloud Fundraising source

# Configuration
- This project creates 8 Reports and 1 Dashboard 
- The Dashboard has 3 default filters added for "All", "Last Week" and "Last Month" that filters all the Reports by the CreatedDate field. 
- You can choose to add more filter options as required. 

## Full list of components

```text
**Reports**
reports/Error_Log_Report_1Ga.report-meta.xml
reports/Failed_and_Pending_Inbound_Reports_jYL.report-meta.xml
reports/Failed_and_Pending_Transactions_jtf.report-meta.xml
reports/Failed_and_Queued_Messages_05k.report-meta.xml
reports/Failed_Payment_Schedules_ZUM.report-meta.xml
reports/Orphan_Installments_2fT.report-meta.xml
reports/Unprocessed_Installments_linked_to_PS_OjT.report-meta.xml
reports/Unprocessed_Transaction_Sets_CSI.report-meta.xml

**Report Folder**
reports/FinDockHealthCheck.reportFolder-meta.xml

**Dashboards**
Dashboards/pvbWarHzQyocvZkvQiAbakDrDoXtef11.dashboard-meta.xml

**Dashboard Folder**
Dashboards/FinDockHealthCheckDashboard.dashboardFolder-meta.xml
```

## Contributing

When contributing to this repository, please first discuss the change you wish to make via an issue or any other method with FinDock before making a change.

## Support

FinDock Labs is a non-supported group in FinDock that releases applications. Despite the name, assistance for any of these applications is not provided by FinDock Support because they are not officially supported features. For a list of these apps, visit the FinDock Labs account on Github.

## License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details
