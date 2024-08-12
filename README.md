# Generating Maven POM from build.gradle

## Generate a `pom.xml`

To generate a `pom.xml` with all version run `gradle  generatePomFileForCustomLibraryPublication`.  
See Artifacts of the latest [Actions](https://github.com/lwluc/gradle-to-maven-pom-demo/actions/workflows/continuous-integration.yml).

The resulting `pom.xml` could be found in `build/publications/customLibrary/pom-default.xml`.

## Generate a `module.json`

To generate a `module.json` with all version run `gradle  generateModuleJson`.  
See Artifacts of the latest [Actions](https://github.com/lwluc/gradle-to-maven-pom-demo/actions/workflows/continuous-integration.yml).

The resulting `module.json` could be found in `build/publications/customLibrary/module.json`.