1. install java 1.8 zulu in mac or window (in window use binary & add path to environment
)
2. install gradle 6.7.1 & then generate wrapper if not already generated `/gradlew wrapper --gradle-version 6.7.1`
3. cross-check correct gradle & java as
    `gradle -v` : if you have installed gradle in your system
    `./gradlew -v` :: if you are using wrapper
4. use terminal `./gradlew build -x test lint` -> the build should be successful
5. use android studio makebuild option -> then use app run