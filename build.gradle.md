## plugins

see [Using Gradle Plugins](https://docs.gradle.org/current/userguide/plugins.html)

`id 'io.spring.dependency-management' version '1.0.9.RELEASE' apply false`



- see Build script blocks -> plugins or PluginContainer plugins (read-only)

- see Build script blocks -> Plugins
Core types -> PluginDependenciesSpec

- see org.gradle.plugin.use.PluginDependenciesSpec plugins(groovy.lang.Closure configuration)


`apply plugin: "groovy"`
- see Applying Binary Plugins
- see `org.gradle.api.plugins.PluginAware void apply(Map<String, ?> options`
- see Build script blocks -> Plugins -> PluginAware.apply(java.util.Map) -> Interface ObjectConfigurationAction
- see [PluginAware](https://docs.gradle.org/current/dsl/org.gradle.api.plugins.PluginAware.html)



## ext
see [Learning More About Build Scripts](https://docs.gradle.org/current/userguide/writing_build_scripts.html) - Declaring variables
see core types - ExtraPropertiesExtension

## configure
see Core types -> Project -> `configure(objects, configureClosure)` and 
`Iterable<?> configure(Iterable<?> objects, Closure configureClosure)`

### dependencyManagement
`Object dependencyManagement(groovy.lang.Closure configuration)`

refers to Controlling Transitives - Sharing Versions
see [Spring Dependency Management Gradle Plugin](https://mvnrepository.com/artifact/io.spring.dependency-management/io.spring.dependency-management.gradle.plugin)
see [io.spring.dependency-management](https://plugins.gradle.org/plugin/io.spring.dependency-management)
see [Dependency Management Plugin](https://github.com/spring-gradle-plugins/dependency-management-plugin)
see [Dependency Management Plugin](https://docs.spring.io/dependency-management-plugin/docs/current-SNAPSHOT/reference/html/)

- http://fasterxml.com/ (faster xml parser)

