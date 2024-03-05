# Goal
* Stack
  * 'spring-boot-starter-web' + 'spring-boot-starter-thymeleaf' + 'spring-boot-starter-security'
    * vs '/hello' the 'spring-boot-starter-security' is the only difference
* All endpoints are secured by default
* If you hit a request without authorization ->
  * 401
  * & you hit from the browser -> you are redirected to default login page!!!!

# How to run locally?
* `./gradlew clean build`
* `./gradlew :bootRun`
  * Check in the logs a generated password!!!

# Notes
* Hit requests in
  * 'requests.http'
  * browser
