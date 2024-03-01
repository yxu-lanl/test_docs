# Class: MetatranscriptomeActivity


_A metatranscriptome activity that e.g. pools assembly and annotation activity._





URI: [nmdc:MetatranscriptomeActivity](https://w3id.org/nmdc/MetatranscriptomeActivity)















```mermaid
classDiagram
  class MetatranscriptomeActivity
    WorkflowExecutionActivity <|-- MetatranscriptomeActivity
    
    
    
  MetatranscriptomeActivity : ended_at_time
    
  MetatranscriptomeActivity : execution_resource
    
  MetatranscriptomeActivity : git_url
    
  MetatranscriptomeActivity : has_failure_categorization
    
    MetatranscriptomeActivity --|> FailureCategorization : has_failure_categorization
    
  MetatranscriptomeActivity : has_input
    
    MetatranscriptomeActivity --|> NamedThing : has_input
    
  MetatranscriptomeActivity : has_output
    
    MetatranscriptomeActivity --|> NamedThing : has_output
    
  MetatranscriptomeActivity : id
    
  MetatranscriptomeActivity : name
    
  MetatranscriptomeActivity : part_of
    
    MetatranscriptomeActivity --|> NamedThing : part_of
    
  MetatranscriptomeActivity : qc_comment
    
  MetatranscriptomeActivity : qc_status
    
    MetatranscriptomeActivity --|> StatusEnum : qc_status
    
  MetatranscriptomeActivity : started_at_time
    
  MetatranscriptomeActivity : type
    
  MetatranscriptomeActivity : used
    
  MetatranscriptomeActivity : version
    
  MetatranscriptomeActivity : was_informed_by
    
    MetatranscriptomeActivity --|> Activity : was_informed_by
    
  

```






## Inheritance
* [Activity](Activity.md)
    * [WorkflowExecutionActivity](WorkflowExecutionActivity.md)
        * **MetatranscriptomeActivity**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [type](type.md) | 1..1 <br/> [String](String.md) | An optional string that specifies the type object | direct |
| [execution_resource](execution_resource.md) | 1..1 <br/> [String](String.md) |  | [WorkflowExecutionActivity](WorkflowExecutionActivity.md) |
| [git_url](git_url.md) | 1..1 <br/> [String](String.md) |  | [WorkflowExecutionActivity](WorkflowExecutionActivity.md) |
| [has_input](has_input.md) | 1..* <br/> [NamedThing](NamedThing.md) | An input to a process | [WorkflowExecutionActivity](WorkflowExecutionActivity.md) |
| [has_output](has_output.md) | 0..* <br/> [NamedThing](NamedThing.md) | An output biosample to a processing step | [WorkflowExecutionActivity](WorkflowExecutionActivity.md) |
| [part_of](part_of.md) | 0..* <br/> [NamedThing](NamedThing.md) | Links a resource to another resource that either logically or physically incl... | [WorkflowExecutionActivity](WorkflowExecutionActivity.md) |
| [version](version.md) | 0..1 <br/> [String](String.md) |  | [WorkflowExecutionActivity](WorkflowExecutionActivity.md) |
| [qc_status](qc_status.md) | 0..1 <br/> [StatusEnum](StatusEnum.md) | Stores information about the result of a process (ie the process of sequencin... | [WorkflowExecutionActivity](WorkflowExecutionActivity.md) |
| [qc_comment](qc_comment.md) | 0..1 <br/> [String](String.md) | Slot to store additional comments about laboratory or workflow output | [WorkflowExecutionActivity](WorkflowExecutionActivity.md) |
| [has_failure_categorization](has_failure_categorization.md) | 0..* <br/> [FailureCategorization](FailureCategorization.md) |  | [WorkflowExecutionActivity](WorkflowExecutionActivity.md) |
| [id](id.md) | 1..1 <br/> [Uriorcurie](Uriorcurie.md) | A unique identifier for a thing | [Activity](Activity.md) |
| [name](name.md) | 0..1 <br/> [String](String.md) | A human readable label for an entity | [Activity](Activity.md) |
| [started_at_time](started_at_time.md) | 1..1 <br/> [String](String.md) |  | [Activity](Activity.md) |
| [ended_at_time](ended_at_time.md) | 1..1 <br/> [String](String.md) |  | [Activity](Activity.md) |
| [was_informed_by](was_informed_by.md) | 0..1 <br/> [Activity](Activity.md) |  | [Activity](Activity.md) |
| [used](used.md) | 0..1 <br/> [String](String.md) |  | [Activity](Activity.md) |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Database](Database.md) | [metatranscriptome_activity_set](metatranscriptome_activity_set.md) | range | [MetatranscriptomeActivity](MetatranscriptomeActivity.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc





## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | nmdc:MetatranscriptomeActivity |
| native | nmdc:MetatranscriptomeActivity |





## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: MetatranscriptomeActivity
description: A metatranscriptome activity that e.g. pools assembly and annotation
  activity.
in_subset:
- workflow subset
from_schema: https://w3id.org/nmdc/nmdc
is_a: WorkflowExecutionActivity
slots:
- type
slot_usage:
  id:
    name: id
    domain_of:
    - Biosample
    - Study
    - NamedThing
    - Activity
    required: true
    structured_pattern:
      syntax: '{id_nmdc_prefix}:wfmt-{id_shoulder}-{id_blade}{id_version}{id_locus}'
      interpolated: true

```
</details>

### Induced

<details>
```yaml
name: MetatranscriptomeActivity
description: A metatranscriptome activity that e.g. pools assembly and annotation
  activity.
in_subset:
- workflow subset
from_schema: https://w3id.org/nmdc/nmdc
is_a: WorkflowExecutionActivity
slot_usage:
  id:
    name: id
    domain_of:
    - Biosample
    - Study
    - NamedThing
    - Activity
    required: true
    structured_pattern:
      syntax: '{id_nmdc_prefix}:wfmt-{id_shoulder}-{id_blade}{id_version}{id_locus}'
      interpolated: true
attributes:
  type:
    name: type
    description: An optional string that specifies the type object.  This is used
      to allow for searches for different kinds of objects.
    deprecated: Due to confusion about what values are used for this slot, it is best
      not to use this slot. See https://github.com/microbiomedata/nmdc-schema/issues/248.
      MAM removed designates_type and rdf:type slot uri 2022-11-30
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    alias: type
    owner: MetatranscriptomeActivity
    domain_of:
    - DataObject
    - Biosample
    - Study
    - OmicsProcessing
    - CreditAssociation
    - WorkflowExecutionActivity
    - MetagenomeAssembly
    - MetagenomeAnnotationActivity
    - MetatranscriptomeAnnotationActivity
    - MetatranscriptomeActivity
    - MagsAnalysisActivity
    - ReadQcAnalysisActivity
    - ReadBasedTaxonomyAnalysisActivity
    - MagBin
    - GenomeFeature
    range: string
    required: true
  execution_resource:
    name: execution_resource
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    domain: Activity
    alias: execution_resource
    owner: MetatranscriptomeActivity
    domain_of:
    - WorkflowExecutionActivity
    range: string
    required: true
  git_url:
    name: git_url
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    alias: git_url
    owner: MetatranscriptomeActivity
    domain_of:
    - WorkflowExecutionActivity
    range: string
    required: true
  has_input:
    name: has_input
    description: An input to a process.
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    domain: NamedThing
    multivalued: true
    alias: has_input
    owner: MetatranscriptomeActivity
    domain_of:
    - BiosampleProcessing
    - OmicsProcessing
    - WorkflowExecutionActivity
    - PlannedProcess
    range: NamedThing
    required: true
  has_output:
    name: has_output
    description: An output biosample to a processing step
    from_schema: https://w3id.org/nmdc/nmdc
    aliases:
    - output
    rank: 1000
    domain: NamedThing
    multivalued: true
    alias: has_output
    owner: MetatranscriptomeActivity
    domain_of:
    - OmicsProcessing
    - WorkflowExecutionActivity
    - PlannedProcess
    range: NamedThing
  part_of:
    name: part_of
    description: Links a resource to another resource that either logically or physically
      includes it.
    from_schema: https://w3id.org/nmdc/nmdc
    aliases:
    - is part of
    rank: 1000
    domain: NamedThing
    slot_uri: dcterms:isPartOf
    multivalued: true
    alias: part_of
    owner: MetatranscriptomeActivity
    domain_of:
    - FieldResearchSite
    - Biosample
    - Study
    - OmicsProcessing
    - WorkflowExecutionActivity
    range: NamedThing
  version:
    name: version
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    domain: Activity
    alias: version
    owner: MetatranscriptomeActivity
    domain_of:
    - WorkflowExecutionActivity
    - ReadQcAnalysisActivity
    range: string
  qc_status:
    name: qc_status
    description: Stores information about the result of a process (ie the process
      of sequencing a library may have for qc_status of 'fail' if not enough data
      was generated)
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    alias: qc_status
    owner: MetatranscriptomeActivity
    domain_of:
    - WorkflowExecutionActivity
    - PlannedProcess
    range: StatusEnum
  qc_comment:
    name: qc_comment
    description: Slot to store additional comments about laboratory or workflow output.
      For workflow output it may describe the particular workflow stage that failed.
      (ie Failed at call-stage due to a malformed fastq file).
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    alias: qc_comment
    owner: MetatranscriptomeActivity
    domain_of:
    - WorkflowExecutionActivity
    - PlannedProcess
    range: string
  has_failure_categorization:
    name: has_failure_categorization
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    multivalued: true
    alias: has_failure_categorization
    owner: MetatranscriptomeActivity
    domain_of:
    - WorkflowExecutionActivity
    - PlannedProcess
    range: FailureCategorization
  id:
    name: id
    description: A unique identifier for a thing. Must be either a CURIE shorthand
      for a URI or a complete URI
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    identifier: true
    alias: id
    owner: MetatranscriptomeActivity
    domain_of:
    - Biosample
    - Study
    - NamedThing
    - Activity
    range: uriorcurie
    required: true
    pattern: ^[a-zA-Z0-9][a-zA-Z0-9_\.]+:[a-zA-Z0-9_][a-zA-Z0-9_\-\/\.,]*$
    structured_pattern:
      syntax: '{id_nmdc_prefix}:wfmt-{id_shoulder}-{id_blade}{id_version}{id_locus}'
      interpolated: true
  name:
    name: name
    description: A human readable label for an entity
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    alias: name
    owner: MetatranscriptomeActivity
    domain_of:
    - Protocol
    - NamedThing
    - PersonValue
    - Activity
    range: string
  started_at_time:
    name: started_at_time
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    domain: Activity
    alias: started_at_time
    owner: MetatranscriptomeActivity
    domain_of:
    - Activity
    range: string
    required: true
    pattern: ^([\+-]?\d{4}(?!\d{2}\b))((-?)((0[1-9]|1[0-2])(\3([12]\d|0[1-9]|3[01]))?|W([0-4]\d|5[0-2])(-?[1-7])?|(00[1-9]|0[1-9]\d|[12]\d{2}|3([0-5]\d|6[1-6])))([T\s]((([01]\d|2[0-3])((:?)[0-5]\d)?|24\:?00)([\.,]\d+(?!:))?)?(\17[0-5]\d([\.,]\d+)?)?([zZ]|([\+-])([01]\d|2[0-3]):?([0-5]\d)?)?)?)?$
  ended_at_time:
    name: ended_at_time
    from_schema: https://w3id.org/nmdc/nmdc
    rank: 1000
    domain: Activity
    alias: ended_at_time
    owner: MetatranscriptomeActivity
    domain_of:
    - Activity
    range: string
    required: true
    pattern: ^([\+-]?\d{4}(?!\d{2}\b))((-?)((0[1-9]|1[0-2])(\3([12]\d|0[1-9]|3[01]))?|W([0-4]\d|5[0-2])(-?[1-7])?|(00[1-9]|0[1-9]\d|[12]\d{2}|3([0-5]\d|6[1-6])))([T\s]((([01]\d|2[0-3])((:?)[0-5]\d)?|24\:?00)([\.,]\d+(?!:))?)?(\17[0-5]\d([\.,]\d+)?)?([zZ]|([\+-])([01]\d|2[0-3]):?([0-5]\d)?)?)?)?$
  was_informed_by:
    name: was_informed_by
    from_schema: https://w3id.org/nmdc/nmdc
    mappings:
    - prov:wasInformedBy
    rank: 1000
    domain: Activity
    alias: was_informed_by
    owner: MetatranscriptomeActivity
    domain_of:
    - Activity
    range: Activity
  used:
    name: used
    from_schema: https://w3id.org/nmdc/nmdc
    mappings:
    - prov:used
    rank: 1000
    domain: Activity
    alias: used
    owner: MetatranscriptomeActivity
    domain_of:
    - Activity
    range: string

```
</details>