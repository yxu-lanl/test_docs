# Slot: qc_status


_Stores information about the result of a process (ie the process of sequencing a library may have for qc_status of 'fail' if not enough data was generated)_



URI: [nmdc:qc_status](https://w3id.org/nmdc/qc_status)



<!-- no inheritance hierarchy -->




## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[WorkflowExecutionActivity](WorkflowExecutionActivity.md) | Represents an instance of an execution of a particular workflow |  no  |
[PlannedProcess](PlannedProcess.md) |  |  no  |
[Pooling](Pooling.md) | physical combination of several instances of like material |  no  |
[Extraction](Extraction.md) | A material separation in which a desired component of an input material is se... |  no  |
[LibraryPreparation](LibraryPreparation.md) |  |  no  |
[CollectingBiosamplesFromSite](CollectingBiosamplesFromSite.md) |  |  no  |
[BiosampleProcessing](BiosampleProcessing.md) | A process that takes one or more biosamples as inputs and generates one or mo... |  no  |
[SubSamplingProcess](SubSamplingProcess.md) | Separating a sample aliquot from the starting material for downstream activit... |  no  |
[MixingProcess](MixingProcess.md) | The combining of components, particles or layers into a more homogeneous stat... |  no  |
[FiltrationProcess](FiltrationProcess.md) | The process of segregation of phases; e |  no  |
[ChromatographicSeparationProcess](ChromatographicSeparationProcess.md) | The process of using a selective partitioning of the analyte or interferent b... |  no  |
[OmicsProcessing](OmicsProcessing.md) | The methods and processes used to generate omics data from a biosample or org... |  no  |
[MetagenomeAssembly](MetagenomeAssembly.md) | A workflow execution activity that converts sequencing reads into an assemble... |  no  |
[MetatranscriptomeAssembly](MetatranscriptomeAssembly.md) |  |  no  |
[MetagenomeAnnotationActivity](MetagenomeAnnotationActivity.md) | A workflow execution activity that provides functional and structural annotat... |  no  |
[MetatranscriptomeAnnotationActivity](MetatranscriptomeAnnotationActivity.md) |  |  no  |
[MetatranscriptomeActivity](MetatranscriptomeActivity.md) | A metatranscriptome activity that e |  no  |
[MagsAnalysisActivity](MagsAnalysisActivity.md) | A workflow execution activity that uses computational binning tools to group ... |  no  |
[MetagenomeSequencingActivity](MetagenomeSequencingActivity.md) | Initial sequencing activity that precedes any analysis |  no  |
[ReadQcAnalysisActivity](ReadQcAnalysisActivity.md) | A workflow execution activity that performs quality control on raw Illumina r... |  no  |
[ReadBasedTaxonomyAnalysisActivity](ReadBasedTaxonomyAnalysisActivity.md) | A workflow execution activity that performs taxonomy classification using seq... |  no  |
[MetabolomicsAnalysisActivity](MetabolomicsAnalysisActivity.md) |  |  no  |
[MetaproteomicsAnalysisActivity](MetaproteomicsAnalysisActivity.md) |  |  no  |
[NomAnalysisActivity](NomAnalysisActivity.md) |  |  no  |







## Properties

* Range: [StatusEnum](StatusEnum.md)





## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: qc_status
description: Stores information about the result of a process (ie the process of sequencing
  a library may have for qc_status of 'fail' if not enough data was generated)
from_schema: https://w3id.org/nmdc/nmdc
rank: 1000
alias: qc_status
domain_of:
- WorkflowExecutionActivity
- PlannedProcess
range: StatusEnum

```
</details>