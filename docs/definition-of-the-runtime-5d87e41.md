<!-- loio5d87e41339d64dc3af4204ab67db12fc -->

# Definition of the Runtime

Introduces the SAP BTP, Kyma runtime and SAP BTP, Cloud Foundry runtime, together with aspects such as who interacts with the platform and the provided tenancy model.

**Defintion of the Runtime**


<table>
<tr>
<th valign="top">

Category

</th>
<th valign="top">

SAP BTP, Kyma runtime

</th>
<th valign="top">

SAP BTP, Cloud Foundry runtime

</th>
</tr>
<tr>
<td valign="top">

Definition

</td>
<td valign="top">

SAP BTP, Kyma runtime is a fully managed Kubernetes runtime based on the open-source project "Kyma". This cloud-native solution allows the developers to extend SAP solutions with serverless Functions and combine them with containerized microservices. The offered functionality ensures smooth consumption of SAP and non-SAP applications, running workloads in a highly scalable environment, and building event- and API-based extensions.

</td>
<td valign="top">

The SAP BTP, Cloud Foundry runtime lets you develop polyglot cloud-native applications and run them on the SAP BTP Cloud Foundry environment.

</td>
</tr>
<tr>
<td valign="top">

Consumption and interaction with the runtime

</td>
<td valign="top">

-   Provisioned in SAP BTP subaccount via [SAP BTP cockpit](https://help.sap.com/docs/btp/sap-business-technology-platform/create-kyma-environment-instance?version=Cloud) or [btp CLI](https://blogs.sap.com/2022/02/24/creating-sap-btp-kyma-runtime-via-the-sap-btp-cli/)

-   Access to Technical UI
-   [Access](https://help.sap.com/docs/btp/sap-business-technology-platform/authentication-in-kyma-environment?version=Cloud) to Kubernetes API
-   [Access control](https://help.sap.com/docs/btp/sap-business-technology-platform/assign-roles-in-kyma-environment?version=Cloud) is managed and handled by the runtime by using Kubernetes RBAC \(Role Based Access Control\)
-   [Commercial integration](https://help.sap.com/docs/btp/sap-business-technology-platform/available-plans-in-kyma-environment?version=Cloud) into SAP BTP subaccount and global account for quota- and entitlement management and cost control



</td>
<td valign="top">

-   Managed and embedded in SAP BTP subaccount via SAP BTP cockpit or btp CLI. See [Getting Started with an Enterprise Account in the Cloud Foundry Environment](https://help.sap.com/docs/btp/sap-business-technology-platform/getting-started-with-enterprise-account-in-cloud-foundry-environment?version=Cloud)

-   Access to Cloud Foundry API
-   [Access control](https://help.sap.com/docs/btp/sap-business-technology-platform/about-user-management-in-cloud-foundry-environment?version=Cloud) is configurable for *Orgs* and *Spaces*
-   Commercial integration into SAP BTP subaccount and global account for quota- and entitlement management and cost control



</td>
</tr>
<tr>
<td valign="top">

Sharing mode

</td>
<td valign="top">

Non-shared cluster based on individual cloud provider subscription.

The cluster is provisioned using the requested virtual machine types from the selected cloud provider in the requested region.

</td>
<td valign="top">

Shared access of cloud provider virtual machines and infrastructure amongst other consumers of the platform in the landscape.

</td>
</tr>
</table>

