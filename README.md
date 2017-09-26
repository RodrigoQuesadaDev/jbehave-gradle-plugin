# JBehave Plugin for Gradle

Gradle plugin to allow for easier usage of [JBehave](http://jbehave.org) in Java and Android projects.

## Usage

Here is a simple example of how to use it in your Gradle project:

```
apply plugin: 'com.rodrigodev.jbehave'

dependencies {
    testCompile "org.jbehave:jbehave-core:$jbehave_version"
    jbehaveSiteResources "org.jbehave:jbehave-core:$jbehave_version"
    jbehaveSiteResources "org.jbehave.site:jbehave-site-resources:$jbehavesite_version:@zip"
}
```

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/RodrigoQuesadaDev/jbehave-gradle-plugin/tags). 

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

