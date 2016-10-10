### Profiles in maven ###

1. run-exec profile activates exec-maven-plugin, which has trigger by package phase

> mvn package -P run-exec

2. only-itest, with-itest profiles used for choosing test configuration.

Run tests without tests from itest package:

> mvn test -P 

run tests only from itest package:

> mvn test -P only-itest

run tests with itest package:

> mvn test -P with-itest

