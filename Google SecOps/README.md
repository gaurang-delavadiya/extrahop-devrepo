# ExtraHop Resources for Extended Integrations

## Dashboards

You can visualize and analyze ingested data by creating dashboards in Google SecOps SIEM.

### Import a Dashboard into Google SecOps SIEM

Complete the following steps to import a dashboard:

1. Download the dashboard `.yaml` file for ExtraHop RevealX from the following [GitHub](https://github.com/ExtraHop/extrahop-devrepo/tree/main/Dashboard) repository.
2. Click the **SIEM Dashboards** section from the navigation panel.
3. Click **Add** and then select **Import Dashboard**.

See [Import Dashboards into Google SecOps](https://cloud.google.com/chronicle/docs/reports/import-export-dashboards#import_dashboards) for more information.

### Import a Native Dashboard into Google SecOps SIEM

Complete the following steps to import a dashboard:

1. Download the dashboard `.json` file for ExtraHop RevealX from the following [GitHub](https://github.com/ExtraHop/extrahop-devrepo/tree/main/Dashboard) repository.
2. On the **Native Dashboards** page, Select **New Dashboard** > **Import from JSON**.
3. Click on **Upload Dashboard files** dialog, browse and select the appropriate JSON file.
4. Click **Edit** to update the name, description, and the dashboard access you're importing.
5. Click **Import** to import the dashboard.

See [Import Dashboards into Google SecOps](https://cloud.google.com/chronicle/docs/reports/manage-native-dashboards#import-dashboards) for more information.


## Create Correlation Rules for Detections and Alerts

Correlation rules scan events ingested into Google SecOps SIEM to generate detections and alerts for specified anomalies. ExtraHop RevealX provides three rules that you can modify or copy to get started. You can find the ExtraHop RevealX correlation rules in the following [GitHub](https://github.com/ExtraHop/extrahop-devrepo/tree/main/Correlation%20Rules) repository.

### Create a New Correlation Rule

1. From Google SecOps SIEM, navigate to **Detections > Rules & Detections**.
2. From the **Rules Editor** tab, click **New**.
3. In the rule editor, clear all the contents, and then copy and paste the code from the GitHub repository.
4. Click **Save New Rule**.
5. To generate alerts from the correlation rule, click the three dots next to the rule name and enable the **Alerting** option.

See [Manage rules using Rules Editor](https://cloud.google.com/chronicle/docs/detection/manage-all-rules#:~:text=Click%20New%20in,click%20DISCARD.) for more information.