# ![LOGO](logo.png) Update Management **flow**ground Connector

## Description

A generated **flow**ground connector for the Update Management API (version 2017-05-15-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/automation-softwareUpdateConfigurationRun/2017-05-15-preview/swagger.json<br/>
Generated at: 2019-06-11T18:13:29+03:00

## API Description

APIs for managing software update configurations.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Return list of software update configuration runs

*Tags:* `Software Update Configuration Run`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.
* `$filter` - _optional_ - The filter to apply on the operation. You can use the following filters: 'properties/osType', 'properties/status', 'properties/startTime', and 'properties/softwareUpdateConfiguration/name'
* `$skip` - _optional_ - Number of entries you skip before returning results
* `$top` - _optional_ - Maximum number of entries returned in the results collection

### Get a single software update configuration Run by Id.

*Tags:* `Software Update Configuration Run`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `softwareUpdateConfigurationRunId` - _required_ - The Id of the software update configuration run.
* `api-version` - _required_ - Client Api Version.
* `clientRequestId` - _optional_ - Identifies this specific client request.

## License

**flow**ground :- Telekom iPaaS / azure-com-automation-software-update-configuration-run-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
