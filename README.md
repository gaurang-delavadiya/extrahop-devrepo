# ExtraHop resources for extended integrations

## Dashboards

You can visualize and analyze ingested data by creating dashboards in SecOps SIEM.

### Import a Dashboard into Google SecOps SIEM

Complete the following steps to import a dashboard:

1. Download the dashboard `.yaml` file for ExtraHop RevealX from the following [GitHub](https://github.com/ExtraHop/extrahop-devrepo/tree/main/Dashboard) repository.
2. Click the **SIEM Dashboards** section from the navigation panel.
3. Click **Add** and then select **Import Dashboard**.

See [Import Dashboards into Google SecOps](https://cloud.google.com/chronicle/docs/reports/import-export-dashboards#import_dashboards) for more information.

## Create Correlation Rules for Detections and Alerts

Correlation rules scan events ingested into the SecOps SIEM to generate detections and alerts for specified anomalies. ExtraHop RevealX provides three rules that you can modify or copy to get started. You can find the ExtraHop RevealX correlation rules in the following [GitHub](https://github.com/ExtraHop/extrahop-devrepo/tree/main/Correlation%20Rules) repository.

### Create a new correlation rule

1. From the SecOps SIEM, navigate to **Detections > Rules & Detections**.
2. From the **Rules Editor** tab, click **New**.
3. In the rule editor, clear all the contents, and then copy and paste the code from the GitHub repository.
4. Click **Save New Rule**.
5. To generate alerts from the correlation rule, click the three dots next to the rule name and enable the **Alerting** option.

See [Manage rules using Rules Editor](https://cloud.google.com/chronicle/docs/detection/manage-all-rules#:~:text=Click%20New%20in,click%20DISCARD.) for more information.