
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

Postman access http:://<ip>:8080 


## Copyright and license
Copyright 2012-2020 ZHENG Ye

Licensed under MIT License (the "License"); You may obtain a copy of the License in the LICENSE file, or at:

https://raw.github.com/dreamhead/moco/master/MIT-LICENSE.txt

## Powered By

<img src="moco-doc/logo_intellij_idea.png?raw=true">
