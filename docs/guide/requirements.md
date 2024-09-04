# Developer Guide

Participants of the dataspace that use VisionsTrust services need to integrate their solution and configure their assets in order for the dataspace to know how to interact with these during data exchange processes. 

This guide will go over the different requirements and steps to do in order to get your first successful data exchange up and running.

## Non Technical Requirements

Let's go over the different things you need to make sure are done before even considering setting up the technical elements for enabling data exchanges.

| Requirement | Why it's needed |
| --- | --- |
| [Onboarding to VisionsTrust](../application/onboarding.md) | Creating an account on VisionsTrust is essential to be registered as a participant of the data space. Without this, your organization will not be recognized in the dataspace and no other participant will be enable to interact with you. |
| [Registering Offers](../application/registering-resources/overview.md) | If you are a data provider, you will need to ensure you have at least one offer available that contains a data resource. If you are a service provider, you will need to ensure you have at least one offer available that contains a service resource. |
| [Creating or joining a project](../application/negotiation/project-negotiation.md) | Data exchanges cannot take place if you are not present in any contract existing in the dataspace. In order to trigger data exchanges with participants that exist in the same contract, you should join or create a project, go through the negotiation processes and then sign that contract (and make sure the other party has signed as well). |

If you or anyone in your organization has already completed these steps, you can move on to the Technical Requirements.

## Technical Requirements

Let's now go over the technical requirements in order for a participant to communicate with a dataspace and more specifically with the VisionsTrust services.

| Requirement | Why it's needed |
| --- | --- |
| [Setting up a Dataspace Connector](./setting-up-a-connector.md) | Each participant in the dataspace needs a way to communicate with the dataspace components and with other participants in the network. Although it is possible to configure a customized implementation of every API needed to ensure secure communication, it is strongly advised to use the open source Prometheus-x Dataspace Connector. |
| [Setting up the technical information of your resources](./setting-up-technical-resources.md) | For a resource to become available in a data exchange, there are some technical information to be setup on the metadata of that resource in the catalogue. Chances are that if a less-technical profile has created your resources, this information might be missing. |

## Actions towards realizing the first data exchange

If all the non technical & technical requirements have been checked off your list, you should be ready to realize your first data exchange.

[Get Started](https://github.com/Prometheus-X-association/dataspace-connector/blob/main/docs/RESOURCE_REPRESENTATION.md){ .md-button }