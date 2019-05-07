# ![LOGO](logo.png) Swagger API-REST for Patrowl Engines **flow**ground Connector

## Description

A generated **flow**ground connector for the Swagger API-REST for Patrowl Engines API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/patrowl.local/1.0.0/openapi.json<br/>
Generated at: 2019-05-07T17:43:37+03:00

## API Description

This is the API documentation for Patrowl Engines usage.

## Authorization

This API does not require authorization.

## Actions

### Index page

> Return index page

*Tags:* `patrowl-engine`

### Clean all scans

> Clean all current scans.

*Tags:* `patrowl-engine`

### Clean scan

> Clean scan identified by id.

*Tags:* `patrowl-engine`

#### Input Parameters
* `scanId` - _required_ - Numeric ID of the scan to clean

### Get findings on finished scans

> Get findings on finished scans.

*Tags:* `patrowl-engine`

#### Input Parameters
* `scanId` - _required_ - Numeric ID of the scan to get findings

### Engine info page

> Return information on engine.

*Tags:* `patrowl-engine`

### Liveness page

> Return liveness page

*Tags:* `patrowl-engine`

### Readiness page

> Return liveness page

*Tags:* `patrowl-engine`

### Configuration reloading page

> Reload the configuration file.

*Tags:* `patrowl-engine`

### Start a new scan

> Start a new scan.

*Tags:* `patrowl-engine`

### Status on all scans

> Status all current scans.

*Tags:* `patrowl-engine`

### Status of a scan

> Status of a scan identified by id.

*Tags:* `patrowl-engine`

#### Input Parameters
* `scanId` - _required_ - Numeric ID of the scan to get status

### Stop a scan

> Stop a scan identified by id.

*Tags:* `patrowl-engine`

#### Input Parameters
* `scanId` - _required_ - Numeric ID of the scan to stop

### Stop all scans

> Stop all current scans.

*Tags:* `patrowl-engine`

### Test page

> Return test page

*Tags:* `patrowl-engine`

## License

**flow**ground :- Telekom iPaaS / patrowl-local-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
