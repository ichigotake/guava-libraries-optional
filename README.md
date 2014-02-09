# guava-libraries-optional

Java "Optional" type from guava-libraries

## Description

 ** This is un-official repository. **

guava-libraries is great library. But in Android application, too big and difficultly config proguard!

So extract `Optional` from official repository.

## Usage

see https://code.google.com/p/guava-libraries/wiki/UsingAndAvoidingNullExplained

## Download

```
repositories {
    maven { url 'https://raw.github.com/ichigotake/guava-libraries-optional/repository' }
}

dependencies {
    compile 'com.google.guava:guava-optional:16.0.1'
}
```

## Proguard

```
-keepattributes *Annotations*
-keepattributes Signature
```

## License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)

