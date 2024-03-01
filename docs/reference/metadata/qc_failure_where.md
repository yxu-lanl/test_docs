# Slot: qc_failure_where


_Describes the nmdc schema class that corresonds to where the failure occurred. Most commonly this would be the same as Class that generated the results._



URI: [nmdc:qc_failure_where](https://w3id.org/nmdc/qc_failure_where)



<!-- no inheritance hierarchy -->




## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[FailureCategorization](FailureCategorization.md) |  |  no  |







## Properties

* Range: [FailureWhereEnum](FailureWhereEnum.md)





## Comments

* If the assembly size was too small to proceed to annotation failure_where would be MetagenomeAssembly.

## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: qc_failure_where
description: Describes the nmdc schema class that corresonds to where the failure
  occurred. Most commonly this would be the same as Class that generated the results.
comments:
- If the assembly size was too small to proceed to annotation failure_where would
  be MetagenomeAssembly.
from_schema: https://w3id.org/nmdc/nmdc
rank: 1000
domain: FailureCategorization
alias: qc_failure_where
domain_of:
- FailureCategorization
range: FailureWhereEnum

```
</details>