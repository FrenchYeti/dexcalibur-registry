# dexcalibur-registry

This repository contains 3 types of plugins which extend analysis accurency and provide additional features.

- `platforms`
- `devices`
- `inspectors`

Each type are described below.

## 1. Platform

When Dexcalibur analyzes an application, it starts by analyzing what the target platform offers - classes/interfaces of Android API, ... Next the application is analyzed, and the references to platform's API are tracked.

So, if you analyze an APK accepting Android Oreo as minimal version but  using sometime a feature introduced into Android P, then calls to Android P only method could not detected.      

This folder contains 

## 2. Device

TODO

## 3. Inspector    

TODO


