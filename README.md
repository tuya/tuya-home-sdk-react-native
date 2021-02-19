>**Note**: This repository is inherited from the [previous Tuya GitHub repository](https://github.com/TuyaInc/tuyasmart-home-sdk-react-native), which will be deprecated soon. Please use this repository for Tuya SDK development instead. For steps about how to change the existing remote repository URL, see [Changing a remote's URL](https://docs.github.com/en/free-pro-team@latest/github/using-git/changing-a-remotes-url)

# tuyasmart-home-sdk-react-native

![](https://img.shields.io/github/license/TuyaInc/tuyasmart-home-sdk-react-native.svg)

## Features

Tuya Smart App SDK provides the interface package for the communication with hardware and Tuya Cloud to accelerate the application development process, including the following features:

- Hardware functions (network configuration, control, status reporting, regular tasks, groups, firmware upgrades, sharing)
- Account system (phone number, email registration, login, password reset and other general account functions)
- Tuya Cloud HTTP API interface package

## Examples

See the demo in [tuyasmart-home-sdk-react-native](https://github.com/TuyaInc/tuyasmart-home-sdk-react-native).

## Constant File

There are many constants are requried to fill in before using App SDK.

```
const appKey=""
const appSecret=""

//login Account
const countryCode=""
const userName=""
const password=""

```

> **Note:** This project is still in the process of debugging and some of functions are not stable.
