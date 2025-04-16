<!-- loio165f1a45bdd747cb94faa4eb888278a4 -->

# Observability

Compare the observability capabilities of SAP BTP, Kyma runtime and SAP BTP, Cloud Foundry runtime.

**Observability**


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

Monitoring

</td>
<td valign="top">

-   Limited support for metrics and dashboarding with SAP Cloud Logging integration; see [Ship Metrics to SAP Cloud Logging](https://help.sap.com/docs/btp/sap-business-technology-platform/integrate-with-sap-cloud-logging?locale=en-US&version=Cloud#ship-metrics-to-sap-cloud-logging)

-   Integration with any vendor-specific Kubernetes APM solution possible




</td>
<td valign="top">

Yes

</td>
</tr>
<tr>
<td valign="top">

Tracing

</td>
<td valign="top">

-   Support for distributed tracing with SAP Cloud Logging integration; see [Ship Distributed Traces to SAP Cloud Logging](https://help.sap.com/docs/btp/sap-business-technology-platform/integrate-with-sap-cloud-logging?locale=en-US&version=Cloud#ship-distributed-traces-to-sap-cloud-logging)

-   Integration with any vendor-specific tracing solution possible based on [OTLP](https://github.com/open-telemetry/opentelemetry-proto/tree/main/docs); see [Traces](https://help.sap.com/docs/BTP/65de2977205c403bbc107264b8eccf4b/f98cda5d058e48ff808ade541a64a6ad.html?locale=en-US)




</td>
<td valign="top">

Zipkin tracing support, see [Supported and Unsupported Cloud Foundry Features](https://help.sap.com/docs/btp/sap-business-technology-platform/cloud-foundry-environment?version=Cloud#supported-and-unsupported-cloud%0Afoundry-features) 

</td>
</tr>
<tr>
<td valign="top">

Logging

</td>
<td valign="top">

-   Supported using SAP Cloud Logging integration; see [Ship Logs to SAP Cloud Logging](https://help.sap.com/docs/btp/sap-business-technology-platform/integrate-with-sap-cloud-logging?locale=en-US&version=Cloud#ship-logs-to-sap-cloud-logging)

-   Integration with any vendor-specific logging solution possible




</td>
<td valign="top">

Yes

</td>
</tr>
<tr>
<td valign="top">

Alerting

</td>
<td valign="top">

Supported using SAP Cloud Logging integration; see [Use SAP Cloud Logging Alerts](https://help.sap.com/docs/btp/sap-business-technology-platform/integrate-with-sap-cloud-logging?locale=en-US&version=Cloud#use-sap-cloud-logging-alerts) 

</td>
<td valign="top">

Yes

</td>
</tr>
</table>

