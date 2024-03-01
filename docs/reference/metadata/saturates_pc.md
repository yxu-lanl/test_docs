# Slot: saturates wt% (saturates_pc)


_Saturate, Aromatic, Resin and Asphaltene¬†(SARA) is an analysis method that divides¬†crude oil¬†components according to their polarizability and polarity. There are three main methods to obtain SARA results. The most popular one is known as the Iatroscan TLC-FID and is referred to as IP-143 (source: https://en.wikipedia.org/wiki/Saturate,_aromatic,_resin_and_asphaltene)_



URI: [MIXS:0000131](https://w3id.org/mixs/0000131)




## Inheritance

* [core_field](core_field.md)
    * **saturates_pc**





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[Biosample](Biosample.md) | Biological source material which can be characterized by an experiment |  no  |







## Properties

* Range: [TextValue](TextValue.md)



## Aliases


* saturates wt%




## Examples

| Value |
| --- |
|  |

## Identifier and Mapping Information





### Annotations

| property | value |
| --- | --- |
| expected_value | name;measurement value || preferred_unit | percent || occurrence | 1 |



### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: saturates_pc
annotations:
  expected_value:
    tag: expected_value
    value: name;measurement value
  preferred_unit:
    tag: preferred_unit
    value: percent
  occurrence:
    tag: occurrence
    value: '1'
description: 'Saturate, Aromatic, Resin and Asphaltene¬†(SARA) is an analysis method
  that divides¬†crude oil¬†components according to their polarizability and polarity.
  There are three main methods to obtain SARA results. The most popular one is known
  as the Iatroscan TLC-FID and is referred to as IP-143 (source: https://en.wikipedia.org/wiki/Saturate,_aromatic,_resin_and_asphaltene)'
title: saturates wt%
examples:
- value: ''
from_schema: https://w3id.org/nmdc/nmdc
aliases:
- saturates wt%
rank: 1000
is_a: core field
string_serialization: '{text};{float} {unit}'
slot_uri: MIXS:0000131
multivalued: false
alias: saturates_pc
domain_of:
- Biosample
range: TextValue

```
</details>