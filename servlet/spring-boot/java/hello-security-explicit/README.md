# Hello Security with Spring MVC
* Used stack
  * Spring Security with the @Beans
    * SecurityFilterChain &
    * UserDetailsService
  * Spring MVC

## How to run locally?
* Via Gradle wrapper -- No local gradle installation required --
  * Ways to run
    * `./gradlew bootRun`
      * Open in your browser 'http://localhost:8080'
    * `./gradlew bootRun` and `java -jar build/libs/hello-security-explicit-6.1.1.jar`
      * Open in your browser 'http://localhost:8080'
* Locally
  * Ways to run
    * `gradle bootRun`
      * Open in your browser 'http://localhost:8080'
    * `gradle bootRun` and `java -jar build/libs/hello-security-explicit-6.1.1.jar`
      * Open in your browser 'http://localhost:8080'

## Notes
* Where does 'LoginPage' & 'LogoutPage' come from ?
* [LogBack](https://logback.qos.ch/)
  * How can it work if there is no dependency added and it's not included by spring automatically?
    * Not found -- `gradle dependencyInsight --dependency ch.qos.logback:logback-core` --
* Why once you run locally and go to 'http://localhost:8080/' -> you are redirected to 'http://localhost:8080/login'?
  