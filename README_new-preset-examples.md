# Build

On Linux x86-64 Ubuntu with C/C++ toolchain, JDK and Maven installed.

```shell
mvn clean install -Djavacpp.platform=linux-x86_64 -Dmaven.test.skip=true -Dmaven.javadoc.skip=true -Dmaven.test.failure.ignore=true
```