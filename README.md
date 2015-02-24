# gradle-modular

Example gradle project with two modules:
 - client
 - server

To install both of them use:
```gradle
 compile 'com.github.jitpack:gradle-modular:1.0'
```
which will return a module that depends on client and server.


To install them individually the syntax `Repo.Module`:

```gradle
 compile 'com.github.jitpack:gradle-modular.client:1.0'
 compile 'com.github.jitpack:gradle-modular.server:1.0'
```

