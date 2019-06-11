# ![LOGO](logo.png) StreamAnalyticsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the StreamAnalyticsManagementClient API (version 2016-03-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/streamanalytics-transformations/2016-03-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:32+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets details about the specified transformation.

*Tags:* `Transformations`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - GUID which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `jobName` - _required_ - The name of the streaming job.
* `transformationName` - _required_ - The name of the transformation.

### Updates an existing transformation under an existing streaming job. This can be used to partially update (ie. update one or two properties) a transformation without affecting the rest the job or transformation definition.

*Tags:* `Transformations`

#### Input Parameters
* `If-Match` - _optional_ - The ETag of the transformation. Omit this value to always overwrite the current transformation. Specify the last-seen ETag value to prevent accidentally overwriting concurrent changes.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - GUID which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `jobName` - _required_ - The name of the streaming job.
* `transformationName` - _required_ - The name of the transformation.

### Creates a transformation or replaces an already existing transformation under an existing streaming job.

*Tags:* `Transformations`

#### Input Parameters
* `If-Match` - _optional_ - The ETag of the transformation. Omit this value to always overwrite the current transformation. Specify the last-seen ETag value to prevent accidentally overwriting concurrent changes.
* `If-None-Match` - _optional_ - Set to '*' to allow a new transformation to be created, but to prevent updating an existing transformation. Other values will result in a 412 Pre-condition Failed response.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - GUID which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `jobName` - _required_ - The name of the streaming job.
* `transformationName` - _required_ - The name of the transformation.

## License

**flow**ground :- Telekom iPaaS / azure-com-streamanalytics-transformations-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
