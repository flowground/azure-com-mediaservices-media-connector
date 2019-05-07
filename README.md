# ![LOGO](logo.png) MediaServicesManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the MediaServicesManagementClient API (version 2015-10-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/mediaservices-media/2015-10-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:23+03:00

## API Description

Media Services resource management APIs.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Media Services REST API operations.

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-10-01.

### Checks whether the Media Service resource name is available. The name must be globally unique.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-10-01.

### Lists all of the Media Services in a resource group.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-10-01.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.

### Deletes a Media Service.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-10-01.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `mediaServiceName` - _required_ - Name of the Media Service.

### Gets a Media Service.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-10-01.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `mediaServiceName` - _required_ - Name of the Media Service.

### Updates a Media Service.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-10-01.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `mediaServiceName` - _required_ - Name of the Media Service.

### Creates a Media Service.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-10-01.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `mediaServiceName` - _required_ - Name of the Media Service.

### Lists the keys for a Media Service.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-10-01.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `mediaServiceName` - _required_ - Name of the Media Service.

### Regenerates a primary or secondary key for a Media Service.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-10-01.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `mediaServiceName` - _required_ - Name of the Media Service.

### Synchronizes storage account keys for a storage account associated with the Media Service account.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2015-10-01.
* `resourceGroupName` - _required_ - Name of the resource group within the Azure subscription.
* `mediaServiceName` - _required_ - Name of the Media Service.

## License

**flow**ground :- Telekom iPaaS / azure-com-mediaservices-media-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
