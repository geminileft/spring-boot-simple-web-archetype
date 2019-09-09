mvn clean install

mvn archetype:generate \
  -DarchetypeGroupId=dev.geminileft \
  -DarchetypeArtifactId=spring-boot-simple-web-archetype

spring-boot:run
