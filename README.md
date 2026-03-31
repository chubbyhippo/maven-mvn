# maven-mvn
## wrapper
```shell
mvn wrapper:wrapper
```
## list
```shell
mvn dependency:list
```
```shell
mvn versions:display-dependency-updates
```
## analyze unused dependencies
```shell
mvn dependency:analyze
```
```shell
mvn dependency:analyze-only
```
## bypass ssl
```sh
mvn package -Dmaven.wagon.http.ssl.insecure=true -Dmaven.wagon.http.ssl.allowall=true -Dmaven.wagon.http.ssl.ignore.validity.dates=true -Dmaven.resolver.transport=wagon
```
