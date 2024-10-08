

# Slot: alternative_term



URI: [IAO:0000118](http://purl.obolibrary.org/obo/IAO_0000118)




## Inheritance

* **alternative_term**
    * [ISA_alternative_term](ISA_alternative_term.md)
    * [IEDB_alternative_term](IEDB_alternative_term.md)
    * [OBO_foundry_unique_label](OBO_foundry_unique_label.md)
    * [synonym](synonym.md)
    * [editor_preferred_term](editor_preferred_term.md)






## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Class](Class.md) |  |  no  |
| [HomoSapiens](HomoSapiens.md) | An individual human being |  no  |
| [Agent](Agent.md) |  |  no  |
| [HasSynonyms](HasSynonyms.md) | a mixin for a class whose members can have synonyms |  no  |
| [Property](Property.md) |  |  no  |
| [AnnotationProperty](AnnotationProperty.md) | A property used in non-logical axioms |  no  |
| [NamedIndividual](NamedIndividual.md) | An instance that has a IRI |  no  |
| [Image](Image.md) |  |  no  |
| [Term](Term.md) | A NamedThing that includes classes, properties, but not ontologies |  no  |
| [ObjectProperty](ObjectProperty.md) | A property that connects two objects in logical axioms |  no  |
| [Subset](Subset.md) | A collection of terms grouped for some purpose |  no  |
| [TransitiveProperty](TransitiveProperty.md) | An ObjectProperty with the property of transitivity |  no  |







## Properties

* Range: [String](String.md)

* Multivalued: True





## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/oak/ontology-metadata




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | IAO:0000118 |
| native | omoschema:alternative_term |
| exact | skos:altLabel |




## LinkML Source

<details>
```yaml
name: alternative_term
in_subset:
- allotrope permitted profile
from_schema: https://w3id.org/oak/ontology-metadata
exact_mappings:
- skos:altLabel
rank: 1000
slot_uri: IAO:0000118
alias: alternative_term
domain_of:
- HasSynonyms
range: string
multivalued: true

```
</details>