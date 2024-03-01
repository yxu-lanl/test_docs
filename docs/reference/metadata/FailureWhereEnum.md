# Enum: FailureWhereEnum




_The permitted values for describing where in the process, either a lab or analysis workflow step, the failure occurred._



URI: [FailureWhereEnum](FailureWhereEnum.md)

## Permissible Values

| Value | Meaning | Description |
| --- | --- | --- |
| OmicsProcessing | None | A failure has occurred in omics processing, a lab process |
| Pooling | None | A failure has occurred in pooling, a lab process |
| Extraction | None | A failure has occurred in extraction, a lab process |
| LibraryPreparation | None | A failure has occurred in library preparation, a lab process |
| MetagenomeAssembly | None | A failure has occurred in metagenome assembly, a workflow process |
| MetatranscriptomeActivity | None | A failure has occurred in metatranscriptome analysis, a workflow process |
| MagsAnalysisActivity | None | A failure has occurred in binning, a workflow process to generate metagenome-... |
| ReadQcAnalysisActivity | None | A failure has occurred in read qc, a workflow process |
| ReadBasedTaxonomyAnalysisActivity | None | A failure has occurred in reads based taxonomy, a workflow process |
| MetagenomeAnnotationActivity | None | A failure has occurred in annotation, a workflow process |




## Slots

| Name | Description |
| ---  | --- |
| [qc_failure_where](qc_failure_where.md) | Describes the nmdc schema class that corresonds to where the failure occurred |






## Comments

* At Chris' recommendation permissible values for this enumeration are the same as Class names.

## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: FailureWhereEnum
description: The permitted values for describing where in the process, either a lab
  or analysis workflow step, the failure occurred.
comments:
- At Chris' recommendation permissible values for this enumeration are the same as
  Class names.
from_schema: https://w3id.org/nmdc/nmdc
rank: 1000
permissible_values:
  OmicsProcessing:
    text: OmicsProcessing
    description: A failure has occurred in omics processing, a lab process.
  Pooling:
    text: Pooling
    description: A failure has occurred in pooling, a lab process.
  Extraction:
    text: Extraction
    description: A failure has occurred in extraction, a lab process.
  LibraryPreparation:
    text: LibraryPreparation
    description: A failure has occurred in library preparation, a lab process.
  MetagenomeAssembly:
    text: MetagenomeAssembly
    description: A failure has occurred in metagenome assembly, a workflow process.
  MetatranscriptomeActivity:
    text: MetatranscriptomeActivity
    description: A failure has occurred in metatranscriptome analysis, a workflow
      process.
  MagsAnalysisActivity:
    text: MagsAnalysisActivity
    description: A failure has occurred in binning, a workflow process to generate
      metagenome-assembled genomes (MAGS).
  ReadQcAnalysisActivity:
    text: ReadQcAnalysisActivity
    description: A failure has occurred in read qc, a workflow process.
  ReadBasedTaxonomyAnalysisActivity:
    text: ReadBasedTaxonomyAnalysisActivity
    description: A failure has occurred in reads based taxonomy, a workflow process.
  MetagenomeAnnotationActivity:
    text: MetagenomeAnnotationActivity
    description: A failure has occurred in annotation, a workflow process.

```
</details>