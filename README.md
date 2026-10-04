# Hotel XML Schema

A compact XML/XSD example for modeling and validating hotel records.

## What it demonstrates

- Reusable complex types for hotel and address data
- Required and optional XML attributes
- One-to-many phone-number support
- Two-letter state-code validation
- A valid sample document and an intentionally invalid sample for testing

## Files

- `Hotels.xsd` — schema and validation rules
- `Hotels.xml` — example hotel data
- `HotelsErrors.xml` — invalid examples for testing schema errors

## Validation

Validate `Hotels.xml` against `Hotels.xsd` with any XML Schema 1.0-compatible validator.
