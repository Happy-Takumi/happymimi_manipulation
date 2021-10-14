# happymimi_manipulation
## Overview
Dynamixelモータ、マニピュレータ全体の制御プログラムや、マニピュレータを用いた物体把持関係のプログラムをまとめたメタパッケージ

## Description
以下のパッケージを含みます。
- ### [dynamixel_controller](./dynamixel_controller)
    > Dynamixelモータの制御プログラムやモジュールをまとめたパッケージ  

    このパッケージでできること
    - マニピュレータの各モータと首モータの角度を取得する
    - マニピュレータや首の制御
    - 物体の受け渡しや配置
    - etc..

- ### [grasping_object](./grasping_object)
    > dynamixel_controllerを用いた物体把持関係をまとめたパッケージ  
    
    このパッケージでできること
    - 認識した物体の把持
    - etc..
    
以上、マニピュレータを用いたモジュールを扱うパッケージとなっています。  

## Requirement
```

```

## Build Environment
```
$ catkin build
```

## Bring Up
基本以下の1つを立ち上げてください  
- recognition_to_graspingの立ち上げ
```
$ roslaunch grasping_object recognition_to_grasping.launch
```

## Usage
モジュールの呼び出し方法等は各種パッケージで記述

## Reverse Lookup
- 認識から把持の一連のタスクを行いたい 👉 [happymimi_manipulation]()
- 物体の認識について 👉 [happymimi_recognition](https://github.com/KIT-Happy-Robot/happymimi_recognition)

---
