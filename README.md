# ![LOGO](logo.png) NASCAR v2 **flow**ground Connector

## Description

A generated **flow**ground connector for the NASCAR v2 API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/nascar-v2/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:33+03:00

## API Description



## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Driver Race Projections (Entry List)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `raceid` - _required_ - Unique FantasyData Race ID.
Example:<code>1</code>, <code>2</code>, etc.

### Driver Details

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `driverid` - _required_ - Unique FantasyData Driver ID.
Example:<code>80000268</code>.

### Drivers

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.

### Race Results

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `raceid` - _required_ - Unique FantasyData Race ID.
Example:<code>1</code>, <code>2</code>, etc.

### Races / Schedule

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `season` - _required_ - Year of the season.
<br>Examples: <code>2015</code>, <code>2016</code>.

### Series

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-nascar-v-2-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
