# Offers

Offers are made available by providers who register data or services on the catalogue.
## What is an offer?

An offer is a set of [data](./data-resources.md) and/or [service](./service-resources.md) resources provided by a participant of the data space, bundled together to form a business & technical product that can be discovered on the catalogue and used by other participants and projects (after negotiating its usage).

### Offer and resource

A resource is the metadata that defines a single unit of data or a single service, used in an offer. An offer can contain several data and service resources. Only offers are visible in the catalogue.

To learn more, see how to create [data](./data-resources.md) resources or [service](./service-resources.md) resources.

### What an offer is composed of

An offer is composed of:

- **General information**: name, caption, description, category... See [Offer page](./offer-settings.md#offer-information).
- **Resources**: the data and/or services the offer comprises. See [Offer page](./offer-settings.md#offer-content).
- **Packages**: the pricing and the usage policies of your offer are grouped in packages. When you create an offer, they are used to create a first package, which includes the resource of the offer. You can add other packages later. See [Offer page](./offer-settings.md#pricing-and-policies).
- **Service levels, commitments & penalties, and termination**: what you guarantee, and what happens if you do not. See [Offer page](./offer-settings.md#service-levels-sla).

!!! note

    For technical profiles, the schema for Offers are based on Gaia-X defined [Service Offerings](https://docs.gaia-x.eu/policy-rules-committee/trust-framework/22.10/service/) and extended to fit the needs of {{ app_name }}.

!!! info

    For more information about policies and what it actually means in the system, please visit the [Prometheus-X Dataspace Connector documentation](https://github.com/Prometheus-X-association/dataspace-connector)
