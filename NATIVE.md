# Native compilation

1. Get a JDK8 compatible GraalVM  
    eg: `sdk install java 21.0.0.2.r8-grl`
   
2. Install native features  
    `gu install native-image`

3. Compile as native image  
    `./gradlew nativeImage`
