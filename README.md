# Procurement Method Type
The extension shows type of Open Procurement procedure.

## Overview
The field introduced by this extension is:
- `tender/procurementMethodType` - Type of Open Procurement procedure.
It should be one of these values: `belowThreshold`,`aboveThresholdUA`,
`aboveThresholdUA.defense`,`aboveThresholdEU`,`reporting`,`negotiation`,
`negotiation.quick`,`competitivedialogue`,`esco`.
## Examples
The following extract illustrates this property in use within the `tender` block.
```.env
{
    "tender": {
        "id": "ocds-213czf-lots-00001-01-tender",
        "title": "Architecture and engineering services",
        "procurementMethodType": "belowThreshold"
    }
}
```