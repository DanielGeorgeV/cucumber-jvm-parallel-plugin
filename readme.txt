mvn install:install-file -Dfile=cucumber-jvm-parallel-plugin-5.0.1-SNAPSHOT.jar -DgroupId=com.e2open-cucumber-parallel -DartifactId=cucumber-jvm-parallel-plugin -Dversion=5.0.1-SNAPSHOT -Dpackaging=maven-plugin




mvn install:install-file -Dfile=cucumber-jvm-parallel-plugin-5.0.1-SNAPSHOT.jar -DgroupId=com.e2open-cucumber-parallel -DartifactId=cucumber-jvm-parallel-plugin -Dversion=5.0.1-SNAPSHOT -Dpackaging=jar -DgeneratePom=true -DcreateChecksum=true



clean compile integration-test -e verify -DforkCount=5 -DfeaturesDirectories=src/test/resources/features/TT/Automated/UI/
