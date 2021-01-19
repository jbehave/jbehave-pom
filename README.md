[![Build Status](https://travis-ci.org/jbehave/jbehave-core.png)](https://travis-ci.org/jbehave/jbehave-pom)

# JBehave

JBehave is a BDD framework for Java and all JVM languages (Groovy, Ruby, Scala).

<img src="http://jbehave.org/reference/preview/images/jbehave-logo.png" alt="JBehave logo" align="right" />

## Using

Canonical information for JBehave:

1. [Web Site](http://jbehave.org).
2. [Stable Reference](http://jbehave.org/reference/stable/).
3. [User mailing list](http://jbehave.org/mailing-lists.html)
4. [Search Maven](http://search.maven.org/#search|ga|1|jbehave)

## Contributing and Developing

Please report issues, feature requests on [JIRA](http://jbehave.org/issue-tracking.html) or discuss them on the
[dev mailing list](http://jbehave.org/mailing-lists.html).

Keep an eye on the  [Travis CI](http://travis-ci.org/jbehave) server for JBehave builds.

### JDK

JDK version required: 

1.8 or above to build (tested with Oracle JDK on different platforms)

The target runtime version is still 1.5 or above.

### Maven 

[Maven](http://maven.apache.org) version required to build: 3.0 or above.

### Encoding

Configure IDE to use UTF-8 for all files
Configure Maven by adding "-Dfile.encoding=UTF-8" to $MAVEN_OPTS

### IDE Integration

Maven is supported in Intellij IDEA out-of-the-box
Maven is supported in Eclipse via [m2e plugin](http://eclipse.org/m2e), included out-of-the-box in some Eclipse distributions.
Eclipse users may also want to load the ides/eclipse/lifecycle-mapping-metadata.xml or ignore the m2e lifecycle mappings manually.

## Related JBehave projects

See also: 

- [jbehave-core](jbehave-core) core functionality of JBehave
- [jbehave-web](jbehave-web) web extensions to JBehave
- [jbehave-osgi](jbehave-osgi) OSGi extensions to JBehave
- [jbehave-eclipse](jbehave-eclipse) Eclipse integration for JBehave
- [jbehave-tutorial](jbehave-tutorial) for an example of JBehave testing of a real web application.

## License

See LICENSE.txt in the source root (BSD).
