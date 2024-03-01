# Slot: has_numeric_value


_Links a quantity value to a number_



URI: [nmdc:has_numeric_value](https://w3id.org/nmdc/has_numeric_value)




## Inheritance

* **has_numeric_value**
    * [has_minimum_numeric_value](has_minimum_numeric_value.md)
    * [has_maximum_numeric_value](has_maximum_numeric_value.md)





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[QuantityValue](QuantityValue.md) | A simple quantity, e |  yes  |
[IntegerValue](IntegerValue.md) | A value that is an integer |  no  |







## Properties

* Range: [Float](Float.md)





## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: has_numeric_value
description: Links a quantity value to a number
from_schema: https://w3id.org/nmdc/nmdc
mappings:
- qud:quantityValue
- schema:value
rank: 1000
domain: QuantityValue
multivalued: false
alias: has_numeric_value
domain_of:
- QuantityValue
- IntegerValue
range: float

```
</details>