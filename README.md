# Adobe Dx ![Build](https://github.com/adobe/adobe-dx/workflows/Build/badge.svg)
[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=com.adobe.dx%3Areactor)](https://sonarcloud.io/dashboard?id=com.adobe.dx%3Areactor)

### Description 

A toolkit for AEM to help build exceptional digital experiences.

#### building DX modules

DX is a set of modules that can be used separately, you can build them all using
 
```mvn```

command at the root of the project.
`all` package contains all modules. 

if you want your build to be directly installed to your local aem instance, just add `install-all` maven profile

```mvn -Pinstall-all``` 

### Contributing

Contributions are welcomed! Read the [Contributing Guide](./.github/CONTRIBUTING.md) for more information.

### Discussion

For ongoing discussions related to adobe-dx, see [the adobe-dx-dev page](https://github.com/orgs/adobe/teams/adobe-dx-devs).

### Licensing

This project is licensed under the Apache V2 License. See [LICENSE](LICENSE) for more information.

