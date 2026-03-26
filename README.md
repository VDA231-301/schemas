# VDA 231‑301 – JSON Schemas
## Official Schema Releases

## Purpose and Scope

This repository contains the **official released JSON Schemas** of the  
**VDA 231‑301 recommendation** for the digital exchange of material‑related test and approval data.

It serves as the **central distribution point for stable schema versions**, including:
- the **generic VDA 231‑301 schema**, and
- the officially released **test‑specific subschemas**.

The schemas published here are intended for productive use in IT systems, software tools, and data exchange processes.

---

## Position within the VDA 231‑301 Ecosystem

Within the VDA 231‑301 ecosystem:
- the **main repository** documents the concept, structure, and development process,
- individual **subschema repositories** support collaborative development and discussion,
- this **schemas repository** provides the **released and versioned schema artifacts**.

Only schemas published in this repository represent an **official released version** of the VDA 231‑301 JSON Schemas.

---

## Stability and Versioning

If someone builds software that depends on version 0.2.0 of a specific subschema, that exact version will always remain accessible at the same location. This level of stability can’t be guaranteed for other repositories.

This guarantees **long‑term stability, reproducibility, and backward compatibility** for productive software implementations.

---

## Access to the Schemas

You can access the schemas directly via GitHub or through GitHub Pages.

The github pages URL is:  
https://vda231-301.github.io/schemas/

Both access paths provide identical content and can be used for validation, implementation, and automated tooling.

---

## Repository Structure

The repository is structured into subdirectories, each representing a specific subschema, listing all its released versions. A subdirectory for the generic (base) schema is also included:

generic/: Contains the base schema versions.  
EN_10204/: Contains versions of specific subschemas.

Additional subdirectories follow the same structure for other released subschemas.

---

## Content of This Repository

This repository contains:
- released versions of the **generic VDA 231‑301 JSON Schema**,
- released versions of **test‑specific subschemas**,
- schema files intended for **validation, implementation, and long‑term reference**.

Each schema version is clearly identified and versioned to support reproducibility and traceability.

---

## Relation to Official VDA Publications

⚠️ **Important clarification:**
- This repository provides **technical schema definitions only**.
- It does **not replace or reproduce** the official VDA documents.
- The **normative and legally binding content** of the VDA 231‑301 recommendation and the referenced test methods is published exclusively by the VDA.

The official documents are available via the **VDA Webshop** and may contain additional information not represented in the JSON Schemas.

---

## Usage

The schemas published in this repository can be used to:
- validate digital test and certificate data,
- implement data exchange interfaces,
- develop converters, validators, and editors,
- integrate VDA 231‑301 into existing IT systems.

They are intended to support **interoperability, automation, and consistent interpretation** of material‑related data across organizational and system boundaries.

---

## Governance and Change Management

All schemas in this repository follow the **formal VDA release and governance process**.

Changes to schemas:
- are discussed and developed in the corresponding repositories,
- are reviewed within the responsible VDA committees,
- become officially released **only after formal approval**.

This ensures stability, traceability, and long‑term reliability for productive implementations.

---

## License

The VDA 231‑301 JSON Schemas are released under the **MIT License**, allowing free use, modification, and distribution.

---

## Contribution

Contributions, feedback, and improvement proposals are welcome.  
Please use the corresponding development repositories for discussions and proposals.

Any contribution intended to become part of an official schema release must follow the formal VDA committee and release process.
