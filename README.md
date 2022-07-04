# JInput

[![Maven Central](https://img.shields.io/maven-central/v/net.java.jinput/coreapi.svg)](https://maven-badges.herokuapp.com/maven-central/net.java.jinput/coreapi)
[![Javadocs](http://www.javadoc.io/badge/net.java.jinput/coreapi.svg)](http://www.javadoc.io/doc/net.java.jinput/coreapi)

Library for access to input devices.

## Building

### Windows

```pwsh
Import-Module "C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\Common7\Tools\Microsoft.VisualStudio.DevShell.dll"
Enter-VsDevShell 2b40cbef
$ENV:MAVEN_HOME="C:\path\to\maven\not\including\bin"
$ENV:ANT_HOME="C:\path\to\ant\not\including\bin"
$ENV:JAVA_HOME="C:\path\to\java\not\including\bin"
$ENV:PATH += ";$ENV:MAVEN_HOME\bin;$ENV:ANT_HOME\bin;$ENV:JAVA_HOME\bin" 
# note that the JAVA part may have to be pre-pended to the PATH if you have another JDK set for your system
mvn package

# note just to build the windows natives, go to src/main/native/ and type `ant` alone.

```

## License
Licensed under [BSD License](https://opensource.org/licenses/BSD-3-Clause), copyright is attributed in each source file committed.
