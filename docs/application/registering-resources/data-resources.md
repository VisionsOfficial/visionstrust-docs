# Data Resources

!!! tip Glossary

    _Check the definition for a Resource in the [glossary](../../glossary.md)_

A data resource is the metadata referencing a single unit of data that a provider can own and propose as a service to the catalogue. This can be metadata about a dataset, database or anything that is technically available for others to access.

Resources are the elements that are used in order to compose an offer, which can be then presented in the catalogue.

!!! info

    A Data Resource alone will never show up in the catalogue. Only the provider of the resource will be able to visualize it unless it is bundled up into an Offer.

## Creating a Data Resource

There are 3 ways to start creating a resource: from the "My Resources" page in the Data tab, on the fly from the "Offer content" page of an offer, or automatically when you create a data offer. The creation flow remains the same in the first two cases.

In our example, we will be showing the flow when you come from an offering creation and want to create a resource on the fly.

### Defining the base information

The first step is to define the base information for your resource. The following is a recap of what should be defined.

<p><img src="../../images/create_data_resource.png" alt="Data resource creation" width="85%"></p>

| Property | Mandatory | Description |
| --- | --- | --- |
| Resource name | yes | The name of your resource, which will be displayed when bundled in an offer |
| Resource type | yes | A category for your resource which helps in categorization purposes |
| Resource description | yes | A description for your resource which helps users of your offer in which this resource is present to understand the contents of your resource |
| Data location | yes | Where the data is located geographically |
| Anonymised extract | yes | A JSON anonymized extract of your data for users to understand the structure of the data they will be receiving |

### Personal Data Information

<p><img src="../../images/data_resource_personal_data.png" alt="Personal data of a data resource" width="85%"></p>

If your data concerns personal data, the Personal Data tab will prompt you to mark this resource as Personal Data and you will optionnally be able to provide a list of descriptions in multiple languages defining your resource to potential end-users that will be giving their consent to share this specific data later down the line.

### Tech Information

<p><img src="../../images/data_resource_configuration.png" alt="Configuration of a data resource" width="85%"></p>

The last section of your resource configuration concerns technical configurations for linkage with the [Dataspace Connectors](https://github.com/Prometheus-X-association/dataspace-connector) and for accessing the resources during data exchanges.

!!! note "For developers"

    If you are a developer, this is defined more extensively in the [Developer documentation](../../guide/setting-up-a-connector.md)

And that's it, once you're done filling it the mandatory & optional information you can add, save the resource and it will be created.

## Finding your resources

Your resources are directly available in the "My Offers" page, in their respective tabs for *Data* and *Services*.

## Configure how your resource is consumed

The "Configuration" step is the technical part of your resource. It allows the actual consumption of your resource by the projects you contract with. You can come back to it later. In "Data Representation", fill in:

- **Protocol type**: how your resource is retrieved by other participants. It decides if the offer is shown as supported on the catalogue: see [Connector & Endpoints](../../settings/connector-endpoints.md).
- **URL** (required): the endpoint at which your resource is accessible. It should probably be a REST API endpoint.
- **Query Parameters** (required): the parameters that the connector can understand when it processes a data request from another participant. Click the **Add text** button to add one. Only the parameters listed here are searched in the URL of the request.

<p><img src="../../images/data_resource_configuration_2.png" alt="The end of the Configuration step" width="85%"></p>

Then fill in:

- **Select MIME type** (required)
- **Proxy**: switch on "Check this box to enable resource proxy" if your resource is reached through a proxy.
- **Output**: the expected technical format of the output, its description, and an anonymized code example of the expected output. Check the last box if the data is aimed to be an API payload, to consume the API of a service provider.

Click the **Save changes** button to save, or **Reset all** to cancel your changes.
