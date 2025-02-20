# 👋 Welcome to RSpace for Ascenscia

  
## Getting started
The project is written in Java, so ofcourse it typically uses Maven for dependency management, and Spring Framework so make sure that's installed. (Since Android Studio is already installed, this should be too if you're developing on the Mobile app too)
```
./mvnw install
```

```
./mvnw spring-boot:run
```

## Running RSpace via docker
- Compile the application into a `rspace.war` file
- Make a new release via GitHub Releases
- In our RSpace VM, we can run a curl on the release link to get the latest war. (MAKE SURE YOU EXPORT AS `rspace.war`
