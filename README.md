[# Build-Stuffz](https://abrehm264.github.io/Build-Stuffz/)

## TC command line params for MSBuild
```bash
/p:Configuration=Release,GenerateSerializationAssemblies=Off,GenerateProjectSpecificOutputFolder=true,OutDir="%system.teamcity.build.checkoutDir%/output",TeamBuildOutDir="%system.teamcity.build.checkoutDir%/output"
```
