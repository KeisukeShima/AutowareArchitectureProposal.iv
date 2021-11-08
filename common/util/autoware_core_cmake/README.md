# autoware_auto_cmake

Provide common CMake variables and functions to [Autoware](https://www.autoware.org/) packages.

Those include:

- Setting the language standard
- Getting user-provided variables
- Providing functions to:
  - set compiler flags
  - turn off optimizations

## Usage

Add `autoware_core_cmake` as a "build_depend" in the dependent packages.

### CMake variables

| Name                 | Type   | Descritpion                                | Default |
| -------------------- | ------ | ------------------------------------------ | ------- |
| `DOWNLOAD_ARTIFACTS` | _BOOL_ | Allow downloading artifacts at build time. | `OFF`   |
