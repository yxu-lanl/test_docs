# Enum: AnalysisTypeEnum



URI: [AnalysisTypeEnum](AnalysisTypeEnum.md)

## Permissible Values

| Value | Meaning | Description |
| --- | --- | --- |
| metabolomics | None |  |
| metagenomics | None | Standard short-read metagenomic sequencing |
| metagenomics_long_read | None | Long-read metagenomic sequencing |
| metaproteomics | None |  |
| metatranscriptomics | None |  |
| natural organic matter | None |  |




## Slots

| Name | Description |
| ---  | --- |
| [analysis_type](analysis_type.md) | Select all the data types associated or available for this biosample |






## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: AnalysisTypeEnum
from_schema: https://w3id.org/nmdc/nmdc
rank: 1000
permissible_values:
  metabolomics:
    text: metabolomics
  metagenomics:
    text: metagenomics
    description: Standard short-read metagenomic sequencing
    title: Metagenomics
  metagenomics_long_read:
    text: metagenomics_long_read
    description: Long-read metagenomic sequencing
    title: Metagenomics (long read)
  metaproteomics:
    text: metaproteomics
  metatranscriptomics:
    text: metatranscriptomics
  natural organic matter:
    text: natural organic matter

```
</details>