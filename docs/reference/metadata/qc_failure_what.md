# Slot: qc_failure_what


_Provides a summary about what caused a lab or workflow process to fail_



URI: [nmdc:qc_failure_what](https://w3id.org/nmdc/qc_failure_what)



<!-- no inheritance hierarchy -->




## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[FailureCategorization](FailureCategorization.md) |  |  no  |







## Properties

* Range: [FailureWhatEnum](FailureWhatEnum.md)





## Comments

* For example Low read count from a sequencer, malformed fastq files, etc)

## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: qc_failure_what
description: Provides a summary about what caused a lab or workflow process to fail
comments:
- For example Low read count from a sequencer, malformed fastq files, etc)
from_schema: https://w3id.org/nmdc/nmdc
rank: 1000
domain: FailureCategorization
alias: qc_failure_what
domain_of:
- FailureCategorization
range: FailureWhatEnum

```
</details>