# Scan and fix security issues in your CloudFormation files

Snyk scans CloudFormation code for misconfigurations and security issues. For configuration files, once scanned, Snyk reports on any misconfigurations based on the settings administrators implement and makes recommendations for fixes accordingly.

## Scan and fix configuration files

* Log in to the account and navigate to the relevant group and organization.

![](../../.gitbook/assets/screenshot-2020-07-09-at-12.43.02.png)

* Re-import repositories if testing occurred before the infrastructure as code feature was enabled in order to detect the CloudFormation code:

  ![Screenshot\_2020-07-09\_at\_12.44.03.png](https://support.snyk.io/hc/article_attachments/360009907118/Screenshot_2020-07-09_at_12.44.03.png)

* Every time a repository is scanned:
  * Every CloudFormation file is imported as a separate project, grouped together per repository, similar to this example:

    ![Screen\_Shot\_2021-06-23\_at\_10.16.38.png](https://support.snyk.io/hc/article_attachments/4402963774865/Screen_Shot_2021-06-23_at_10.16.38.png)

  * If the repository was re-imported: in order to then import the CloudFormation files, Snyk imports and re-tests the existing application manifest files--displaying the test time as "now".
* Click a project link to view the scan results and to help view details on the CloudFormation code:![Screen\_Shot\_2021-06-23\_at\_10.18.49.png](https://support.snyk.io/hc/article_attachments/4402963775377/Screen_Shot_2021-06-23_at_10.18.49.png)
