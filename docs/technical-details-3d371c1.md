<!-- loio3d371c16241b472fbf12196a114cddf7 -->

# Technical Details

Compare the technical details for SAP BTP, Kyma runtime and SAP BTP, Cloud Foundry runtime.

**Technical Details**


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

Based on open source and open standards

</td>
<td valign="top">

Based on Kyma [open source](https://kyma-project.io/#/), augmented by [Istio](https://istio.io/), [Open Telemetry](https://opentelemetry.io/), and SAP proprietary extensions.

</td>
<td valign="top">

Based on Cloud Foundry [open source](https://www.cloudfoundry.org/), augmented by HAProxy, [BOSH](https://bosh.io/docs/), and SAP proprietary extensions.

</td>
</tr>
<tr>
<td valign="top">

Supported buildpacks

</td>
<td valign="top">

Cloud Native Buildpacks

</td>
<td valign="top">

SAP-managed and Cloud Foundry community buildpacks for several [development languages](https://help.sap.com/docs/btp/sap-business-technology-platform/development-languages?locale=en-US&version=Cloud) 

</td>
</tr>
<tr>
<td valign="top">

SAP BTP service support

</td>
<td valign="top">

Yes

</td>
<td valign="top">

Yes

</td>
</tr>
<tr>
<td valign="top">

Internal network support

</td>
<td valign="top">

Yes

</td>
<td valign="top">

No

See [Supported and Unsupported Cloud Foundry Features](https://help.sap.com/docs/btp/sap-business-technology-platform/cloud-foundry-environment?version=Cloud#supported-and-unsupported-cloud%0Afoundry-features)

</td>
</tr>
<tr>
<td valign="top">

CI/CD support

</td>
<td valign="top">

Yes, see [Roadmap](https://roadmaps.sap.com/board?PRODUCT=73554900100800001771&range=CURRENT-LAST#Q4%202023) 

</td>
<td valign="top">

Yes

</td>
</tr>
<tr>
<td valign="top">

Service mesh support

</td>
<td valign="top">

Yes

</td>
<td valign="top">

No

</td>
</tr>
<tr>
<td valign="top">

Elasticity

</td>
<td valign="top">

Yes

</td>
<td valign="top">

Yes

</td>
</tr>
<tr>
<td valign="top">

Autoscaling support

</td>
<td valign="top">

Yes

</td>
<td valign="top">

Yes, with the Application Autoscaler service.

See [Application Autoscaler](https://help.sap.com/docs/application-autoscaler/application-autoscaler/what-is-application-autoscaler?version=Cloud&locale=en-US) and SAP Discovery Center: [Application Autoscaler](https://discovery-center.cloud.sap/serviceCatalog/application-autoscaler?tab=feature&region=all&service_plan=standard&commercialModel=cpea).

</td>
</tr>
<tr>
<td valign="top">

Speed of autoscaling

</td>
<td valign="top">

App scaling speed depends on startup time of the workload.

Vertical scale-up \(by adding more Kubernetes Nodes to the cluster\): < 1 min

</td>
<td valign="top">

App scaling speed depends on startup time of the workload

</td>
</tr>
<tr>
<td valign="top">

Partial zone outage detection

</td>
<td valign="top">

Yes

</td>
<td valign="top">

Yes

</td>
</tr>
<tr>
<td valign="top">

In-system build & deploy using buildpacks

</td>
<td valign="top">

No

</td>
<td valign="top">

Yes

</td>
</tr>
<tr>
<td valign="top">

Platform-as-a-service: MTA support

</td>
<td valign="top">

No

</td>
<td valign="top">

Yes

</td>
</tr>
<tr>
<td valign="top">

Identity provisioning support

</td>
<td valign="top">

No

</td>
<td valign="top">

No

</td>
</tr>
<tr>
<td valign="top">

Custom domains

</td>
<td valign="top">

Yes

See [Set up a custom domain for a workload](https://kyma-project.io/#/api-gateway/user/tutorials/01-10-setup-custom-domain-for-workload)

</td>
<td valign="top">

Yes

See [SAP Custom Domain Service](https://help.sap.com/docs/custom-domain?locale=en-US&version=Cloud)

</td>
</tr>
<tr>
<td valign="top">

Transport services

</td>
<td valign="top">

No

For Kyma, use Helm charts and a CI/CD pipeline. See [Delivery Options](https://help.sap.com/docs/btp/btp-admin-guide/delivering-applications?locale=en-US&version=Cloud#delivery-options).

</td>
<td valign="top">

Yes

See [SAP Cloud Transport Management](https://discovery-center.cloud.sap/serviceCatalog/cloud-transport-management?region=all)

</td>
</tr>
<tr>
<td valign="top">

Connectivity

</td>
<td valign="top">

Yes

</td>
<td valign="top">

Yes

</td>
</tr>
<tr>
<td valign="top">

Task and Jobs support

</td>
<td valign="top">

Yes

</td>
<td valign="top">

Yes

See [Supported and Unsupported Cloud Foundry Features](https://help.sap.com/docs/btp/sap-business-technology-platform/cloud-foundry-environment?version=Cloud#supported-and-unsupported-cloud%0Afoundry-features)

</td>
</tr>
<tr>
<td valign="top">

RFC connection support

</td>
<td valign="top">

Yes

</td>
<td valign="top">

Yes

</td>
</tr>
</table>

