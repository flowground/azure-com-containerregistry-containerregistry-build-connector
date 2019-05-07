# ![LOGO](logo.png) ContainerRegistryManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ContainerRegistryManagementClient API (version 2018-09-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/containerregistry-containerregistry_build/2018-09-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:51+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get the upload location for the user to be able to upload the source.

*Tags:* `Registries`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.

### Gets all the runs for a registry.

*Tags:* `Runs`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.
* `$filter` - _optional_ - The runs filter to apply on the operation. Arithmetic operators are not supported. The allowed string function is 'contains'. All logical operators except 'Not', 'Has', 'All' are allowed.
* `$top` - _optional_ - $top is supported for get list of runs, which limits the maximum number of runs to return.

### Gets the detailed information for a given run.

*Tags:* `Runs`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.
* `runId` - _required_ - The run ID.

### Patch the run properties.

*Tags:* `Runs`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.
* `runId` - _required_ - The run ID.

### Cancel an existing run.

*Tags:* `Runs`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.
* `runId` - _required_ - The run ID.

### Gets a link to download the run logs.

*Tags:* `Runs`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.
* `runId` - _required_ - The run ID.

### Schedules a new run based on the request parameters and add it to the run queue.

*Tags:* `Registries`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.

### Lists all the tasks for a specified container registry.

*Tags:* `Tasks`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.

### Deletes a specified task.

*Tags:* `Tasks`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.
* `taskName` - _required_ - The name of the container registry task.

### Get the properties of a specified task.

*Tags:* `Tasks`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.
* `taskName` - _required_ - The name of the container registry task.

### Updates a task with the specified parameters.

*Tags:* `Tasks`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.
* `taskName` - _required_ - The name of the container registry task.

### Creates a task for a container registry with the specified parameters.

*Tags:* `Tasks`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.
* `taskName` - _required_ - The name of the container registry task.

### Returns a task with extended information that includes all secrets.

*Tags:* `Tasks`

#### Input Parameters
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `api-version` - _required_ - The client API version.
* `taskName` - _required_ - The name of the container registry task.

## License

**flow**ground :- Telekom iPaaS / azure-com-containerregistry-containerregistry-build-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
