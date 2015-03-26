# gradle-modular

Example gradle project with two modules:
 - client
 - server

To install both of them at the same time use:
```gradle
 compile 'com.github.jitpack:gradle-modular:1.1'
```
which will return a module that depends on client and server.


To install them individually the syntax `com.github.User.Repo` for groupId:

```gradle
 compile 'com.github.jitpack.gradle-modular:client:1.1'
 compile 'com.github.jitpack.gradle-modular:server:1.1'
```

