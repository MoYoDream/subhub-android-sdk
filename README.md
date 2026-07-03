# SubHub Android SDK 0.1.0

Maven coordinates:

```kotlin
implementation("dev.subhub:subhub:0.1.0")
```

Add to `settings.gradle.kts`:

```kotlin
maven {
    url = uri("https://maven.pkg.github.com/MoYoDream/subhub-android-sdk")
    credentials {
        username = providers.gradleProperty("gpr.user").get()
        password = providers.gradleProperty("gpr.key").get()
    }
}
```
