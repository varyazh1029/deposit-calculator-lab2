# deposit-calculator (ЛР №2, БГУИР, каф. ЭИ)

Требуется JDK 17, Ant 1.10.x (+ ant-junitlauncher), Maven 3.9.x.

## Ant
    ./get-libs.sh        # один раз, скачать JUnit JAR в lib/
    ant -p
    ant clean all        # clean -> test -> report -> jar
    ant run

## Maven
    mvn clean verify
    mvn surefire-report:report   # HTML: target/site/surefire-report.html

## Gradle (доп.)
    gradle wrapper --gradle-version 9.8   # один раз
    ./gradlew build
