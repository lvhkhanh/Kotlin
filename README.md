# Kotlin
## Prerequisites
### http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
### https://www.jetbrains.com/help/idea/install-and-set-up-product.html
## Official
### https://kotlinlang.org/docs/mobile/setup.html
### https://developer.android.com/kotlin/learn
### https://kotlinlang.org/
## Labs
### https://codelabs.developers.google.com/codelabs/java-friendly-kotlin/index.html?index=..%2F..index
### https://developer.android.com/courses/kotlin-bootcamp

## Courses
### https://www.coursera.org/learn/kotlin-for-java-developers
### https://www.codecademy.com/learn/learn-kotlin
### https://codelabs.developers.google.com/codelabs/android-room-with-a-view-kotlin/#0
### https://codelabs.developers.google.com/codelabs/kotlin-coroutines/#0
### https://www.udacity.com/course/kotlin-bootcamp-for-programmers--ud9011 Approx. 2 Weeks
### https://codelabs.developers.google.com/kotlin-bootcamp/
### https://app.pluralsight.com/search/?q=kotlin
### https://codelabs.developers.google.com/codelabs/basic-android-kotlin-training-welcome/index.html?index=..%2F..index#0
### https://codelabs.developers.google.com/codelabs/build-your-first-android-app-kotlin/index.html?index=..%2F..index#0
### https://kotlinlang.org/docs/reference/basic-syntax.html
### https://kotlinlang.org/docs/reference/java-interop.html
### https://kotlinlang.org/docs/reference/coding-conventions.html
### https://kotlinlang.org/docs/reference/comparison-to-java.html
### https://play.kotlinlang.org/hands-on/overview
### https://play.kotlinlang.org/byExample/overview
### https://play.kotlinlang.org/koans/overview
### https://www.udacity.com/course/kotlin-for-android-developers--ud888
### https://www.udacity.com/course/advanced-android-with-kotlin--ud940
### https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012
### https://www.coursera.org/programs/b0a28d35-70b0-4126-bfa1-27d2636e6420/browse?query=Kotlin
## Paths
### https://app.pluralsight.com/paths/skill/android-development-with-kotlin-fundamentals
## Cert
### https://developers.google.com/certification/associate-android-developer
https://codelabs.developers.google.com/codelabs/java-to-kotlin/index.html?index=..%2F..index#0



https://developer.android.com/kotlin

https://en.wikipedia.org/wiki/Kotlin_(programming_language)

https://github.com/JetBrains/kotlin

https://www.infoworld.com/article/3224868/what-is-kotlin-the-java-alternative-explained.html

https://blog.jetbrains.com/kotlin/


## IDE
### IntelliJ
### Visual Studio Code
#### Extension
##### ext:kt
## Notes
### Data types
#### Always capitalized: Int, String, Boolean
```
#compile
kotlinc HelloWorld.kt -include-runtime -d HelloWorld.jar
#run
java -jar HelloWorld.jar

kotlinc-js
kotlinc-native
```
## Mapping
|   |Kotlin   |Python   |   |   |
|---|---|---|---|---|
|   | var list = mutablelistOf(Type(), Type())  |list = ["a","b"]   |   |   |
|   |fun getDestinationIndex(destination){}   |def get_destination_index(destination): <br> &nbsp;&nbsp;pass   |   |   |
|   |val destinationIndex = destinations.indexOf(destination)   |destination_index = destinations.index(destination)   |   |   |
|   |destinations.add(destination)   |destinations.append(destination)   |   |   |
|   |println("text")   |print("text")   |   |   |
|   |objectNameCouldNull?.property   |  |   |   |
|   |objectNameCouldNull?:defaultValue  |  |   |   |
| switch  |when   |   |   |   |
|   |try {<br>} catch (ErrorType ex) {<br>}   |try: <br> // ... <br> except ErrorType: <br> //...   |   |   |
|   |object SingletonName   |   |   |   |
