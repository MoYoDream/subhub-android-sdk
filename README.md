# SubHub Android SDK 1.0.0

Maven coordinates:

```kotlin
implementation("dev.subhub:subhub:1.0.0")
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
