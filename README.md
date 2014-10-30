ubuntu-14.04-oracle-java-1.7
============================


## Summary

Docker image with Ubuntu 14.04 and Oracle Java 1.7.

Published to Docker Hub as [fernandoacorreia/ubuntu-14.04-oracle-java-1.7](https://registry.hub.docker.com/u/fernandoacorreia/ubuntu-14.04-oracle-java-1.7/) via automated build.


## Installation

```
$ docker pull fernandoacorreia/ubuntu-14.04-oracle-java-1.7
```


## Usage

The main purpose is for use as a base image for Java-based applications. But if you'd like to use the CLI, here are some examples:


#### Run `java`

```
$ docker run --rm fernandoacorreia/ubuntu-14.04-oracle-java-1.7
```


#### Run `javac`

```
$ docker run --rm fernandoacorreia/ubuntu-14.04-oracle-java-1.7 javac
```


### Open a command prompt inside a temporary container

```
$ docker run --rm -it fernandoacorreia/ubuntu-14.04-oracle-java-1.7 bash
```


### License

Using this image implies accepting Oracle's [License](http://www.oracle.com/technetwork/java/javase/terms/license/index.html).


## Release notes

### 2014-10-30
- java version "1.7.0_72"
- Ubuntu 14.04.1 LTS
- Linux 3.13.0-24-generic x86_64
