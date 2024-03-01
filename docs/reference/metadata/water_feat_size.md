# Slot: water feature size (water_feat_size)


_The size of the water feature_



URI: [MIXS:0000223](https://w3id.org/mixs/0000223)




## Inheritance

* [core_field](core_field.md)
    * **water_feat_size**





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[Biosample](Biosample.md) | Biological source material which can be characterized by an experiment |  no  |







## Properties

* Range: [QuantityValue](QuantityValue.md)



## Aliases


* water feature size




## Examples

| Value |
| --- |
|  |

## Identifier and Mapping Information





### Annotations

| property | value |
| --- | --- |
| expected_value | measurement value || preferred_unit | square meter || occurrence | 1 |



### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: water_feat_size
annotations:
  expected_value:
    tag: expected_value
    value: measurement value
  preferred_unit:
    tag: preferred_unit
    value: square meter
  occurrence:
    tag: occurrence
    value: '1'
description: The size of the water feature
title: water feature size
examples:
- value: ''
from_schema: https://w3id.org/nmdc/nmdc
aliases:
- water feature size
rank: 1000
is_a: core field
slot_uri: MIXS:0000223
multivalued: false
alias: water_feat_size
domain_of:
- Biosample
range: QuantityValue

```
</details>