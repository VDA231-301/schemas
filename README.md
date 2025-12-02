# Purpose of the Schemas Repository

This repository exists to make all released versions of the base schema and its subschemas permanently available. That’s why it’s also referred to as the delivery repository – it serves as the delivery source for the JSON Schema artifacts.

If someone builds software that depends on version `0.2.0` of a specific subschema, that exact version will always remain accessible at the same location. This level of stability can’t be guaranteed for other repositories.

# Repository Structure
The repository is structured into subdirectories, each representing a specific subschema, listing all its released versions. A subdirectory for the generic (base) schema is also included:
- `generic/`: Contains the base schema versions.
- `EN_10204/`: Contains versions of specific subschemas.

# Accessing the Schemas
You can access the schemas directly via GitHub or through GitHub Pages. 
The github pages URL is:
https://vda231-301.github.io/schemas/
