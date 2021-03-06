# Specification characteristic relationship Data Model

## Domain

The  schema is part of the  Domain

## Description

An aggregation, migration, substitution, dependency or exclusivity relationship between/among productSpecCharacteristics.

## Data model

A JSON Schema corresponding to this data model can be found
[here](https://github.com/tmforum-rand/schemas/blob/candidates/Common/SpecificationCharacteristicRelationship.schema.json).

The Data model is defined as shown below:

- `href` : Hyperlink reference to the target SpecificationCharacteristic

  - Optional


- `id` : Unique identifier of the target SpecificationCharacteristic

  - Optional


- `name` : Name of the target SpecificationCharacteristic

  - Optional


- `relationshipType` : Type of relationship such as aggregation, migration, substitution, dependency, exclusivity

  - Optional


- `validFor` : The period for which the SpecificationCharacteristicRelationship is valid

  - Optional






## TMForum APIs that use this schema

Taking into consideration the snapshot of 04/02/2020 04:59:16 UTC the list of [TMForum Open APIs](https://www.tmforum.org/open-apis/) that uses this schemas is:

Coming soon