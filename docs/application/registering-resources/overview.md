# Offers

Offers are made available from providers registering Data or Services on the catalogue with a set of information related to both the technical & business product that offer is comprised of.

## What is an offer ?

An offer is a set of [data](./data.md) and/or [service](./services.md) resources provided by a participant of the data space, bundled together to form a business & technical product that can be discovered on the catalogue and used by other participants and projects (after negotiating its usage).

### Differences with a resource

A resource is the metadata that defines a single unit of data or a single service. Resources are not directly present in the catalogue and form your own _catalogue_ of assets that you can then bundle up into offers for the catalogue.

You can find more information on both in looking at how to create [data](./data.md) resources or how to create [service](./services.md) resources.

## Composition of an Offer

Let's go over what is comrpised in an offer, as well as what information is mandatory or optional.

> For technical profiles, the schema for Offers are based on Gaia-X defined [Service Offerings](https://docs.gaia-x.eu/policy-rules-committee/trust-framework/22.10/service/) and extended to fit the needs of VisionsTrust.

### General Information

| Property | Mandatory | Description |
| --- | --- | --- |
| Name | yes | The name of your offer |
| Caption | yes | A short caption to describe your offer for it to be quickly understood when displayed on the catalogue |
| Description | no | A longer description, with rich text support to fully define your offer |
| Category | yes | A list of categories that your offer fits into. This is essential for matching it with projects and providing recommendations. |
| Location | yes | The location in which your offer operates / is stored. |
| Image | no | If set, will be displayed in the catalogue, otherwise, your organization logo will be displayed |

### Resources

| Property | Mandatory | Description |
| --- | --- | --- |
| Data Resources | yes if no service resources are set | The list of data resources this offer is comprised of |
| Service Resources | yes if no data resources are set | The list of service resources this offer is comprised of |

### Pricing

| Property | Mandatory | Description |
| --- | --- | --- |
| Subscription pricing | yes | The cost of your offer |
| Billing period | yes | If a billing period is applicable, the billing period that corresponds to your offer |
| Setup fee | no | If applicable, a setup fee for your offer |
| Cost per API call | no | If applicable, how much an API call to your service costs |
| Currency | yes | The currency used by your offer pricing information |
| Pricing description | no | Free text for any additionnal pricing information that should be known by users of your offer |

### Policies

Regarding access & usage control, policies should be defined on your offer for them to be configured during the negotiation phase for your offering. By default, a **No restriction** policy will be set, meaning that your data has no extra rules to be accessed once a contract for a data exchange on that offer can be enforced.

Setting anything other than **No Restriction** will require you to configure it when your offer is being negotiated either between you and another participant or for its usage in a project.

> For more information about policies and what it actually means in the system, please visit the [Prometheus-X Dataspace Connector documentation](https://github.com/Prometheus-X-association/dataspace-connector)
