# Kernel recommendations:

### Redmi note 8/8T (*ginkgo*/willow)
- Support in other ROMS is not guaranteed. Non RDP/Non Dynamic ROMs only.

Note: while the kernel doesn't have major modifications, no official support is provided if you're using a report bugs while using this kernel.


# Kernel Labels:

The kernel label uses the following format:
- `buildDate-deviceName-buildType-kernelVariant-runNumber`
As an example you can see:
- `2025.06.18-XXX-KSU

### buildDate
The date the kernel was built following the format: `YYYY.MM.DD`.
### deviceName
The name of the device the kernel is built for, like `MiA3`.
### buildType
The type of the build, it can be the following:
- Normal (empty)
- KSU (-KSU)
- RKSU (-RKSU)
- KSUN (-KSUN)

For SUSFS variants, the buildType receives a `.SUSFS` suffix.
### runNumber
Simply the number of the github run, don't use this as a definitive versioning metric, always base yourself on the build date.

# Credits:

**Kernel Sources**:
- [@Skyblueborb](https://github.com/Skyblueborb) -> SM6125, NoName 18.1
- [@aleeeee1](https://github.com/aleeeee1) -> 'heresy' mic fix kernel
- [@PowerX-NOT](https://github.com/PowerX-NOT) -> NoName VIC
- [@RainySorcerer](https://github.com/RainySorcerer) -> Snowflake

**Workflow/Patches**:
- [@TheWildJames](https://github.com/TheWildJames) -> workflow reference, patches
- [@simonpunk](https://gitlab.com/simonpunk) -> susfs patches
- [@sidex15](https://github.com/sidex15) -> susfs patches
