<!-- loiode5c964bd17443409e11c55f4f5dacb7 -->

# Comparison: SAP BTP, Kyma Runtime and SAP BTP, Cloud Foundry Runtime

In SAP BTP, you have the choice between several runtimes.



If you want to run ABAP, you'll choose the [SAP BTP ABAP environment](https://help.sap.com/docs/sap-btp-abap-environment/abap-environment/abap-environment). Hence, this document only compares the non-ABAP runtimes SAP BTP, Cloud Foundry runtime and SAP BTP, Kyma runtime.

Both runtimes can be used to host and run your custom code, while at the same time being connected to SAP BTP Multi-Cloud Services and your on-premise systems. Depending on your use case and the skill set of your developers, choose the runtime that fits your needs.

> ### Note:  
> The following tables serve as an index into the available public documentation helping you to compare SAP’s non-ABAP runtimes.
> 
> *Last update: November 2024*



<a name="loiode5c964bd17443409e11c55f4f5dacb7__section_al2_g3t_xyb"/>

## Business Aspects Drive the Decision

The difference and the main decision point is your application architecture, driven by business aspects. Usually, scaling patterns and economies of scale drive certain requirements towards the implementation of the business logic. That logic can vary from very simplistic pieces down to very complex chains of logic.

Some architectural patterns need more control over the infrastructure. Simple implementations of business logic need less infrastructure control.



<a name="loiode5c964bd17443409e11c55f4f5dacb7__section_phb_f3t_xyb"/>

## No Difference in Non-Functionals

Both non-ABAP runtimes offer parity with regards to non-functionals. Both bring multi-availability-zone infrastructure support and the same SLA levels. Applications do benefit from high availability of the runtime and can run in high availability mode themselves. Both runtimes are managed for you by SAP.



<a name="loiode5c964bd17443409e11c55f4f5dacb7__section_lmn_h3t_xyb"/>

## Decide Only When You Have To

Because the runtimes don't differ from a non-functional point of view, you don't have to take the decision up front. If your business grows and your scaling requirements or use cases grow or change, then you can augment your current architecture with more infrastructure by adding certain use cases on either runtime of choice. The decision which runtime to use doesn't need to be binary. It can very well be a combination of the two.

**Related Information**  


[Definition of the Runtime](definition-of-the-runtime-5d87e41.md "Provides a definition of the SAP BTP, Kyma runtime and SAP BTP, Cloud Foundry runtime, based on aspects such as who interacts with the platform, what the required skills are, and the provided tenancy model.")

[Runtime Strategy and Roadmap](runtime-strategy-and-roadmap-792ca4a.md "Both runtime offerings are a fundamental part of SAP BTP’s runtime service offerings and are part of SAP’s long term strategy and commitment. This section shows where you find the relevant material.")

[Offerings by the Runtime Service](offerings-by-the-runtime-service-e9ab9cb.md "This section provides general information about the runtime offerings. Both runtimes in the focus of this comparison provide the same level of service.")

[Development Skills](development-skills-d14a56a.md "Learn about the target users and the development skills they need.")

[Security and Resilience](security-and-resilience-ef639ea.md "Learn about the security and resilience aspects.")

[Archetypes](archetypes-19cdc9e.md "Compare the archetypes supported by SAP BTP, Kyma runtime and SAP BTP, Cloud Foundry runtime.")

[Protocols](protocols-3fcdd4d.md "Compare protocols supported by SAP BTP, Kyma runtime and SAP BTP, Cloud Foundry runtime.")

[Observability](observability-165f1a4.md "Compare the observability capabilities of SAP BTP, Kyma runtime and SAP BTP, Cloud Foundry runtime.")

[Technical Details](technical-details-3d371c1.md "Compare the technical details for SAP BTP, Kyma runtime and SAP BTP, Cloud Foundry runtime.")

[Sizing](sizing-4846163.md "Compare the sizing for SAP BTP, Kyma runtime and SAP BTP, Cloud Foundry runtime.")

[Other Information](other-information-7942e45.md "Compare other information for SAP BTP, Kyma runtime and SAP BTP, Cloud Foundry runtime.")

