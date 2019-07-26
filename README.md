# ![LOGO](logo.png) groupalarm Monitor API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm Monitor API API (version 1.16.0).

Generated from: https://app.groupalarm.com/api/v1/monitor<br/>
Generated at: 2019-07-26T13:59:34+03:00

## API Description

The monitor service implements all monitor functions for GroupAlarm<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### ListMonitors
> Returns all monitors for the given organization<br/>

*Tags:* `monitor`

#### Input Parameters
* `organization` - _required_ - ID of the organization of which the monitors should be listed<br/>

### EditMonitor
> Updates a given monitor with new values<br/>

*Tags:* `monitor`

### CreateMonitor
> Creates a new Monitor<br/>

*Tags:* `monitor`

### GetMonitor
> Returns the Monitor for the given Monitor-ID<br/>

*Tags:* `monitor`

#### Input Parameters
* `monitor_id` - _required_ - ID of the Monitor that should be fetched<br/>

### DeleteMonitor
> Deletes the given monitor by ID<br/>

*Tags:* `monitor`

#### Input Parameters
* `monitor_id` - _required_ - The ID of the monitor that should be deleted<br/>

### GetMonitorData
> Returns all data for a given monitor<br/>

*Tags:* `monitor-data`

#### Input Parameters
* `monitor_id` - _required_ - The ID of the monitor<br/>

### SetMonitorDataAlarming
> Create or overwrites the monitor alarming data<br/>

*Tags:* `monitor-data`

#### Input Parameters
* `monitor_id` - _required_ - ID of the monitor which data should be updated<br/>

### UpdateMonitorDataAlarming
> Patches one or more field from the monitor alarming data<br/>

*Tags:* `monitor-data`

#### Input Parameters
* `monitor_id` - _required_ - ID of the monitor which data should be updated<br/>

### SetMonitorDataMeta
> Create or overwrites the monitor meta data<br/>

*Tags:* `monitor-data`

#### Input Parameters
* `monitor_id` - _required_ - ID of the monitor which data should be updated<br/>

### UpdateMonitorDataMeta
> Patches one or more field from the monitor meta data<br/>

*Tags:* `monitor-data`

#### Input Parameters
* `monitor_id` - _required_ - ID of the monitor which data should be updated<br/>

## License

**flow**ground :- Telekom iPaaS / groupalarm-monitor-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
