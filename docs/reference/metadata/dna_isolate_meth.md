# Slot: DNA isolation method (dna_isolate_meth)


_Describe the method/protocol/kit used to extract DNA/RNA._



URI: [nmdc:dna_isolate_meth](https://w3id.org/nmdc/dna_isolate_meth)



<!-- no inheritance hierarchy -->




## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[Biosample](Biosample.md) | Biological source material which can be characterized by an experiment |  no  |







## Properties

* Range: [String](String.md)

* Recommended: True



## Aliases


* Sample Isolation Method




## Examples

| Value |
| --- |
| phenol/chloroform extraction |

## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: dna_isolate_meth
description: Describe the method/protocol/kit used to extract DNA/RNA.
title: DNA isolation method
examples:
- value: phenol/chloroform extraction
from_schema: https://w3id.org/nmdc/nmdc
aliases:
- Sample Isolation Method
rank: 16
string_serialization: '{text}'
alias: dna_isolate_meth
domain_of:
- Biosample
slot_group: JGI-Metagenomics
range: string
recommended: true

```
</details>