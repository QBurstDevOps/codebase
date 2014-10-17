# Pull nodejs base image
FROM qburstdevops/base

# Bundle app source
COPY . /mnt


CMD ["java", "-cp", "/mnt/target/sampleproj-1.0-SNAPSHOT.jar com.sample.App"]
