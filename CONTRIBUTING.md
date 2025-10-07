# Contributing

To contribute your configurations to this project, please follow the below steps:

1. [Fork](https://github.com/3DCoded/MMU-Tip-Configs/fork) this repository.
2. Duplicate one of the template files: [Tip Cutting](https://github.com/3DCoded/MMU-Tip-Configs/blob/main/TEMPLATE-cut-tip.cfg) or [Tip Forming](https://github.com/3DCoded/MMU-Tip-Configs/blob/main/TEMPLATE-form-tip.cfg)
3. Rename your duplicate in the following format: `TOOLHEAD-EXTRUDER-HOTEND.cfg`.
4. Update the `[metadata]` section in your config to match your setup.
5. Copy-and-paste your relevant configurations into the file. Both tip forming and cutting parameters are generally found in `mmu_macro_vars.cfg`.
6. Under each copied section, add a `_file` parameter that describes which file it originally came from under the `mmu/base/` directory.
  Example:

```ini
[gcode_macro _MMU_FORM_TIP_VARS]
_file: mmu_macro_vars.cfg
variable_extruder_eject_speed: 10
```

7. Submit a [Pull Request](https://github.com/3DCoded/MMU-Tip-Configs/compare).

Thank you for your contribution to this project!
