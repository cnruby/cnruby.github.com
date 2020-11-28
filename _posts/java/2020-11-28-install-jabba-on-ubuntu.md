---
layout: page
title:  "Hello jabba!"
tagline: "</br>Java Version Manager"
date:   2020-11-28 15:24:35 +0200
tags: [Java, JVM, Zulu, JDK, jabba]
categories: java
---

## install jabba on Ubuntu 20.04

```bash
# insatll jabba
curl -sL https://github.com/shyiko/jabba/raw/master/install.sh | bash && . ~/.jabba/jabba.sh
```

## install JDK on Ubuntu 20.04

```bash
# Java 8
jabba install zulu@~1.8.272
# Java 11
jabba install zulu@1.11.0-9
```

## use Java 8 with jabba
```bash
echo "zulu@1.8.272" > .jabbarc
cat .jabbarc
jabba use
#ONLY the follow command, NOT `java --version`
java -version
echo $JAVA_HOME
type java
```

# use Java 11 with jabba
```bash
echo "zulu@1.11.0-9" > .jabbarc
cat .jabbarc
jabba use
java --version
# OR
java -version
echo $JAVA_HOME
type java
```

## use default Java 11
```bash
# open a shell
jabba alias default zulu@1.11.0-9

# open new shell
java --version
# OR
java -version
```

## use default Java 8
```bash
# open a shell
jabba alias default zulu@1.8.272

#open new shell
# ONLY
java -version
```


## References
- https://github.com/shyiko/jabba
- JDK! https://developer.okta.com/blog/2019/01/16/which-java-sdk
