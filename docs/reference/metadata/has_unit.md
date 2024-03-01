# Slot: has_unit


_Links a QuantityValue to a unit_



URI: [nmdc:has_unit](https://w3id.org/nmdc/has_unit)



<!-- no inheritance hierarchy -->




## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[QuantityValue](QuantityValue.md) | A simple quantity, e |  yes  |







## Properties

* Range: [Unit](Unit.md)



## Aliases


* scale



## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: has_unit
description: Links a QuantityValue to a unit
from_schema: https://w3id.org/nmdc/nmdc
aliases:
- scale
mappings:
- qud:unit
- schema:unitCode
rank: 1000
domain: QuantityValue
alias: has_unit
domain_of:
- QuantityValue
range: unit

```
</details>