# Setting up the Prometheus-X Dataspace Connector

The Prometheus-X Dataspace Connector (PDC) is an important service that each participant in the dataspace must have in order to run secure and controlled data exchanges regulated by the contracts signed within the Prometheus-X ecosystem.

As VisionsTrust is an implementation of Prometheus-X services, it is designed to work with any other Prometheus-X implementation, thus making the PDC a must have for all participants using VisionsTrust.

## Why it is needed

The PDC regulates data exchanges in the Prometheus-X ecosystem. It has many features to verify validity of contracts, enforce policies on the access of resources, manage end-user consent authorizations and provide a large set of methods to ease the communication with Prometheus-X services (and thus VisionsTrust services as well).

Although an implementation without the PDC can be done, it would require a participant to implement themselves everything from webhooks for the data exchange protocol to contract verification solutions, policy enforcement points, consent management, data processing chain support and more in order to have the full capabilities of any other participant that communicates with the Prometheus-X Dataspace.

This is why the usage of the PDC is strongly recommended. In any case, the PDC being an open source project, you are free to fork it and add any custom extension to it as you see fit. And if you have any interesting extension to propose to the community, feel free to contribute to the project.

## Installation

To install the PDC, please follow the README file defined in the [Prometheus-X Dataspace Connector](https://github.com/Prometheus-X-association/dataspace-connector) GitHub repository which will guide through everything you need to know to get the connector up and running.

## Configuration

When you reach the configuration phase of your connector and need to setup some config variables regarding the services to use, this is where you will need to configure your connector to point to the VisionsTrust services. The configuration should be set as followed:

| Var | URI |
| --- | --- |
| catalogUri | [https://api.visionstrust.com/v1/](https://api.visionstrust.com/v1/) |
| contractUri | [https://contract.visionstrust.com/](https://contract.visionstrust.com/) |
| consentUri | [https://consent.visionstrust.com/v1](https://consent.visionstrust.com/v1) |

If your `config.json` file is properly configured to communicate with VisionsTrust, it should have automatically registered your connector for your account on VisionsTrust.

To check this, you can go into your VisionsTrust profile settings and click on the Endpoints tab to see if it has been correctly setup with your connector. Endpoints should point towards the https:// domain where your connector is currently running.

## Optional: Credentials

As defined in this section of the GitHub documentation for the PDC, you can optionnally setup credentials per resource that you define in the VisionsTrust Catalogue. Each credential you generate will provide you with an identifier that you can then setup in the metadata of your resource.

> Please ensure you setup the credential identifier and not the credential value itself. The system is set to work with credential identifiers so only your connector knows how to handle them and nobody else than you has access to the value of your credential used to communicate with your resource.
