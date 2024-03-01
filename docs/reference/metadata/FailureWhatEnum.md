# Enum: FailureWhatEnum




_The permitted values for describing where a failure occurred during processing in the lab during analysis workflows._



URI: [FailureWhatEnum](FailureWhatEnum.md)

## Permissible Values

| Value | Meaning | Description |
| --- | --- | --- |
| low_read_count | None | Number of output reads is not sufficient to continue to the next analysis ste... |
| malformed_data | None | Workflow failure reading input or writing the output file(s) |
| assembly_size_too_small | None | The size of the metagenome or metatranscriptome assembly is too small to proc... |
| no_valid_data_generated | None | A process ran but did not produce any output |
| other | None | A lab process or analysis workflow has failed in a way that has not been capt... |




## Slots

| Name | Description |
| ---  | --- |
| [qc_failure_what](qc_failure_what.md) | Provides a summary about what caused a lab or workflow process to fail |






## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: FailureWhatEnum
description: The permitted values for describing where a failure occurred during processing
  in the lab during analysis workflows.
from_schema: https://w3id.org/nmdc/nmdc
rank: 1000
permissible_values:
  low_read_count:
    text: low_read_count
    description: Number of output reads is not sufficient to continue to the next
      analysis step.
  malformed_data:
    text: malformed_data
    description: Workflow failure reading input or writing the output file(s).
  assembly_size_too_small:
    text: assembly_size_too_small
    description: The size of the metagenome or metatranscriptome assembly is too small
      to proceed to the next analysis workflow.
  no_valid_data_generated:
    text: no_valid_data_generated
    description: A process ran but did not produce any output. Ie binning ran but
      did not produce any medium or high quality bins.
  other:
    text: other
    description: A lab process or analysis workflow has failed in a way that has not
      been captured by the available values yet. Please use slot 'qc_comment' to specify
      details.

```
</details>