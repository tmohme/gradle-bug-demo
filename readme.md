# Reproduction
## Gradle
* Run `./gradlew dependencies --configuration compile`
* => `org.apache.wicket:wicket-extensions` gets resolved to 6.15.0

## Maven
* Run `./mvnw dependency:tree`
* => `org.apache.wicket:wicket-extensions` gets resolved to 7.4.0
