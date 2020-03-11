
Based on Moco framework(https://github.com/dreamhead/moco).

## Quick Start

* Clone Moco

```shell
git clone https://github.com/xuyaozhong/moco1400.git
```
* Build Moco

```shell
./gradlew build
```
* Build uberjar

```shell
./gradlew uberjar
```
* Check code before commit

```shell
./gradlew check
```

## On ubuntu18.04

* Stop firwall and nginx

```shell
./stopfwnginx.sh
```

* Fast build project

```shell
./build.sh
```

* Mock GAT 1400 REST API

```shell
./run.sh
```

Postman access http:://ip:8080 

## On Windows
Download [Standalone Runner](https://github.com/xuyaozhong/moco1400/blob/master/moco-runner/build/libs/moco-runner-1.1.0-uber.jar)

Run HTTP server with the configuration file.
```shell
java -jar moco-runner-1.1.0-uber.jar http -p 8080 -g settings.json
```
* Now, open your favorite browser to visit http://localhost:8080.

