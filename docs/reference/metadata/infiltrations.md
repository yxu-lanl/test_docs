# Slot: infiltrations


_The amount of time it takes to complete each infiltration activity_



URI: [nmdc:infiltrations](https://w3id.org/nmdc/infiltrations)



<!-- no inheritance hierarchy -->




## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[Biosample](Biosample.md) | Biological source material which can be characterized by an experiment |  no  |







## Properties

* Range: [String](String.md)

* Multivalued: True

* Regex pattern: `^(?:[0-9]|[1-9][0-9]|9[0-9]|0[0-9]|0[0-5][0-9]):[0-5][0-9]:[0-5][0-9]$`



## Aliases


* infiltration_1
* infiltration_2




## Examples

| Value |
| --- |
| ['00:01:32', '00:00:53'] |

## See Also

* [https://www.protocols.io/view/field-sampling-protocol-kqdg3962pg25/v1](https://www.protocols.io/view/field-sampling-protocol-kqdg3962pg25/v1)

## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: infiltrations
description: The amount of time it takes to complete each infiltration activity
examples:
- value: '[''00:01:32'', ''00:00:53'']'
from_schema: https://w3id.org/nmdc/nmdc
see_also:
- https://www.protocols.io/view/field-sampling-protocol-kqdg3962pg25/v1
aliases:
- infiltration_1
- infiltration_2
rank: 1000
multivalued: true
list_elements_ordered: true
alias: infiltrations
domain_of:
- Biosample
range: string
pattern: ^(?:[0-9]|[1-9][0-9]|9[0-9]|0[0-9]|0[0-5][0-9]):[0-5][0-9]:[0-5][0-9]$

```
</details>