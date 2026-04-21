# diamond-nomenclature-definitions
Nomenclature definitions for diamond-nomenclature (additions or overrides to common-definitions)


## Purpose and connection with other repositories

This repository contains codelists for the DIAMOND project that are
compatible with the [nomenclature](https://github.com/IAMconsortium/nomenclature) Python package. It is used by the
packages [i2amparis/nomenclature-template](https://github.com/i2amparis/nomenclature-template) and [i2amparis/new-validation-ui](https://github.com/i2amparis/new-validation-ui) for validating
model, scenario, variable and region names and units, and for defining
aggregation mappings between regions.

Definitions of variables in this repository come in addition to or override ones
given in the [common-definitions](https://github.com/IAMconsortium/common-definitions) repository. 

## Organization

Codelist definitions are stored in the `/definitions/` folder, and region
mappings in the `/mappings/` folder, like for any `nomenclature` definitions
repository.

Each of these folders contain a subfolder named `common-definitions-overrides`,
which contains definitions that override existing definitions in
`common-definitions`. These subfolders generally mirror the subfolder structures
and file names in the `common-definitions` repository. Files and subfolders
outside of `common-definitions-overrides` are additional definitions that are
not present in `common-definitions`.
