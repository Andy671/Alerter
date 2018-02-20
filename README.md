# Alerter 2.0.4 Unofficial AndyMod

It's a quick fix of the missing feature of the [Alerter library](https://github.com/Tapadoo/Alerter).
I've added Slide In and Slide Out Interpolator option to configure.

## Gradle

```groovy
dependencies {
    implementation 'com.github.Andy671:Alerter:v2.0.4AndyMod'
}
```

## Usage
When constructing the Alerter

```java
.setSlideInInterpolator(new SomeAndroidInterpolator())
.setSlideOutInterpolator(new SomeAndroidInterpolator())
```