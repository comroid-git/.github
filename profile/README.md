### Using comroid Java Libraries

All of comroid's Java Libraries are hosted in a [dedicated repository](https://maven.comroid.org).

Here's the usual copy-pasta:

#### Maven
```
<repositories>
    <repository>
        <name>comroid</name>
        <url>https://maven.comroid.org</url>
    </repository>
</repositories>
```

#### Gradle
```
repositories {
    maven { url = "https://maven.comroid.org" }
}
```
