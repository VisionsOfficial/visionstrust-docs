# Glossary

The dataspace vocabulary can be combursome to deal with as there are many terms that can sound similar and that aren't always representing the same entity. This glossary can be used as reference for the main terms used throughout this documentation and that usually applies to the Prometheus-X ecosystem as well.

| Term | Definition |
| --- | --- |
| Participant | An entity (usually an organisation) that has an identifier in the dataspace. A participant can be a Data/Service/Infrastructure provider or a project (use-case) orchestrator. |
| Project | A project or use-case orchestrated by a participant inside which multiple participants are members and which defines a scoped ecosystem of data exchanges between its members. |
| Resource | A data or software (API, service...) resource that is proposed from a provider to the marketplace. It is the asset metadata representation of a resource that is owned by a provider. A resource is not presented in the marketplace if not packaged into a Service Offering. |
| Offer | A package of one or more resources of a provider containing some additional information in order to be proposed to the marketplace. Unlike resources, Service Offerings are meant for display and discovery in the marketplace. |
| Data Provider | A participant that proposes Service Offerings based of data resources on the marketplace |
| Service Provider | A participant that proposes Service Offerings based of services (AI service, API...) on the marketplace |
| Infrastructure Service Offer | A service implementing a Prometheus-X Building Block that can be used in service chains within data space use cases. |
| Infrastructure Provider | A participant that proposes an infrastructure service on the marketplace |
| Service Chain | A representation of a complex workflow of data sequences between offers of multiple members of a single project |
| Contract | The object representing the data sharing agreement either between multiple members in the case of a Data Space Use Case contract or between 2 participants in the case of a bilateral contract |
| Orchestrator | The participant who creates and leads a project. It invites the offers it needs and negotiates their terms with the providers. |
| Join request | A request sent by a participant to join a project. The orchestrator then chooses which offers of this participant to invite. |
| Basket | The place where an orchestrator gathers the offers it wants, assigns them to a project, adjusts their terms and sends the negotiation to the providers. |
| Package | A formula of an offer, with its own price, resources and usage policies. An offer has from one to three packages, and the orchestrator chooses one in the basket. |
| Baseline | The terms that the orchestrator proposes for an offer when it starts a negotiation, such as the contract duration, the renewal mode and the usage policies. |
| Negotiation | The exchange between an orchestrator and the provider of an offer to agree on the terms of use of the offer in a project. It goes on in rounds until one side accepts or declines. |
| Round | One exchange of proposals in a negotiation. |
| Renegotiation | A finished negotiation that is opened again to change its terms, to change the package of an offer, or to add offers. |
| Contribution | An offer that the orchestrator adds to its own project, with the policies and the pricing that apply to this project. |
| Exit request | The withdrawal of one offer from a project, requested by the participant or proposed by the orchestrator, and approved or rejected by the other side. The participant stays in the project. |
| Template | Values that you save once, for offers or for projects, and use again when you create them. |
| PDC | The Prometheus-X Dataspace Connector, the connector that a participant uses to exchange data in the data space. |
| PDCaaS | The Prometheus-X Dataspace Connector as a Service: a connector hosted by VisionsTrust, that a participant deploys with one click from its settings. |
| DVCT | The Data Value Chain Tracker, the implementation of a Prometheus-X building block that a service chain can use. The connectors use it during the exchanges, and it needs an additional configuration of the connectors. |
