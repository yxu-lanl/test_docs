# Slot: nitrogen (nitro)


_Concentration of nitrogen (total)_



URI: [MIXS:0000504](https://w3id.org/mixs/0000504)




## Inheritance

* [core_field](core_field.md)
    * **nitro**





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[Biosample](Biosample.md) | Biological source material which can be characterized by an experiment |  no  |







## Properties

* Range: [QuantityValue](QuantityValue.md)



## Aliases


* nitrogen




## Examples

| Value |
| --- |
| 4.2 micromole per liter |

## Identifier and Mapping Information





### Annotations

| property | value |
| --- | --- |
| expected_value | measurement value || preferred_unit | micromole per liter || occurrence | 1 |



### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: nitro
annotations:
  expected_value:
    tag: expected_value
    value: measurement value
  preferred_unit:
    tag: preferred_unit
    value: micromole per liter
  occurrence:
    tag: occurrence
    value: '1'
description: Concentration of nitrogen (total)
title: nitrogen
examples:
- value: 4.2 micromole per liter
from_schema: https://w3id.org/nmdc/nmdc
aliases:
- nitrogen
rank: 1000
is_a: core field
slot_uri: MIXS:0000504
multivalued: false
alias: nitro
domain_of:
- Biosample
range: QuantityValue

```
</details>