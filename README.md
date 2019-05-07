# ![LOGO](logo.png) ApplicationClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApplicationClient API (version 2018-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/resources-managedapplications/2018-06-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:46+03:00

## API Description

ARM applications

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets all the applications within a subscription.

*Tags:* `Applications`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Lists the managed application definitions in a resource group.

*Tags:* `ApplicationDefinitions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Deletes the managed application definition.

*Tags:* `ApplicationDefinitions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `applicationDefinitionName` - _required_ - The name of the managed application definition to delete.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Gets the managed application definition.

*Tags:* `ApplicationDefinitions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `applicationDefinitionName` - _required_ - The name of the managed application definition.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Creates a new managed application definition.

*Tags:* `ApplicationDefinitions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `applicationDefinitionName` - _required_ - The name of the managed application definition.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Gets all the applications within a resource group.

*Tags:* `Applications`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Deletes the managed application.

*Tags:* `Applications`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `applicationName` - _required_ - The name of the managed application.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Gets the managed application.

*Tags:* `Applications`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `applicationName` - _required_ - The name of the managed application.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Updates an existing managed application. The only value that can be updated via PATCH currently is the tags.

*Tags:* `Applications`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `applicationName` - _required_ - The name of the managed application.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Creates a new managed application.

*Tags:* `Applications`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `applicationName` - _required_ - The name of the managed application.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Deletes the managed application.

*Tags:* `Applications`

#### Input Parameters
* `applicationId` - _required_ - The fully qualified ID of the managed application, including the managed application name and the managed application resource type. Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/Microsoft.Solutions/applications/{application-name}
* `api-version` - _required_ - The API version to use for this operation.

### Gets the managed application.

*Tags:* `Applications`

#### Input Parameters
* `applicationId` - _required_ - The fully qualified ID of the managed application, including the managed application name and the managed application resource type. Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/Microsoft.Solutions/applications/{application-name}
* `api-version` - _required_ - The API version to use for this operation.

### Updates an existing managed application. The only value that can be updated via PATCH currently is the tags.

*Tags:* `Applications`

#### Input Parameters
* `applicationId` - _required_ - The fully qualified ID of the managed application, including the managed application name and the managed application resource type. Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/Microsoft.Solutions/applications/{application-name}
* `api-version` - _required_ - The API version to use for this operation.

### Creates a new managed application.

*Tags:* `Applications`

#### Input Parameters
* `applicationId` - _required_ - The fully qualified ID of the managed application, including the managed application name and the managed application resource type. Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/Microsoft.Solutions/applications/{application-name}
* `api-version` - _required_ - The API version to use for this operation.

## License

**flow**ground :- Telekom iPaaS / azure-com-resources-managedapplications-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
