# Slot: has_raw_value


_The value that was specified for an annotation in raw form, i.e. a string. E.g. "2 cm" or "2-4 cm"_



URI: [nmdc:has_raw_value](https://w3id.org/nmdc/has_raw_value)



<!-- no inheritance hierarchy -->




## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[AttributeValue](AttributeValue.md) | The value for any value of a attribute for a sample |  no  |
[QuantityValue](QuantityValue.md) | A simple quantity, e |  yes  |
[ImageValue](ImageValue.md) | An attribute value representing an image |  no  |
[PersonValue](PersonValue.md) | An attribute value representing a person |  yes  |
[TextValue](TextValue.md) | A basic string value |  no  |
[UrlValue](UrlValue.md) | A value that is a string that conforms to URL syntax |  no  |
[TimestampValue](TimestampValue.md) | A value that is a timestamp |  no  |
[IntegerValue](IntegerValue.md) | A value that is an integer |  no  |
[BooleanValue](BooleanValue.md) | A value that is a boolean |  no  |
[ControlledTermValue](ControlledTermValue.md) | A controlled term or class from an ontology |  no  |
[ControlledIdentifiedTermValue](ControlledIdentifiedTermValue.md) | A controlled term or class from an ontology, requiring the presence of term w... |  no  |
[GeolocationValue](GeolocationValue.md) | A normalized value for a location on the earth's surface |  yes  |







## Properties

* Range: [String](String.md)





## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nmdc/nmdc




## LinkML Source

<details>
```yaml
name: has_raw_value
description: The value that was specified for an annotation in raw form, i.e. a string.
  E.g. "2 cm" or "2-4 cm"
from_schema: https://w3id.org/nmdc/nmdc
rank: 1000
domain: AttributeValue
multivalued: false
alias: has_raw_value
domain_of:
- AttributeValue
- QuantityValue
range: string

```
</details>