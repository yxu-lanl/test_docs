# Slot: size-fraction lower threshold (size_frac_low)


_Refers to the mesh/pore size used to pre-filter/pre-sort the sample. Materials larger than the size threshold are excluded from the sample_



URI: [MIXS:0000735](https://w3id.org/mixs/0000735)




## Inheritance

* [core_field](core_field.md)
    * **size_frac_low**





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[Biosample](Biosample.md) | Biological source material which can be characterized by an experiment |  no  |







## Properties

* Range: [QuantityValue](QuantityValue.md)



## Aliases


* size-fraction lower threshold




## Examples

| Value |
| --- |
| 0.2 micrometer |

## Identifier and Mapping Information





### Annotations

| property | value |
| --- | --- |
| expected_value | value || preferred_unit | micrometer || occurrence | 1 |



### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: size_frac_low
annotations:
  expected_value:
    tag: expected_value
    value: value
  preferred_unit:
    tag: preferred_unit
    value: micrometer
  occurrence:
    tag: occurrence
    value: '1'
description: Refers to the mesh/pore size used to pre-filter/pre-sort the sample.
  Materials larger than the size threshold are excluded from the sample
title: size-fraction lower threshold
examples:
- value: 0.2 micrometer
from_schema: https://w3id.org/nmdc/nmdc
aliases:
- size-fraction lower threshold
rank: 1000
is_a: core field
slot_uri: MIXS:0000735
multivalued: false
alias: size_frac_low
domain_of:
- Biosample
range: QuantityValue

```
</details>