# @titanium/coremotion

[![@titanium/coremotion](https://img.shields.io/npm/v/@titanium/coremotion.png)](https://www.npmjs.com/package/@titanium/coremotion)


> Native modules that allows you to use iOS CoreMotion framework with Axway Titanium native mobile apps.

* [📝 Description](#-description)
* [🚀 Getting Started](#-getting-started)
	* [Install `@titanium/coremotion` in root of project](#install-titaniumcoremotion-in-root-of-project)
		* [Example](#example)
* [✨Features](#features)
* [Library versions:](#library-versions)
* [📚Learn More](#learn-more)
* [📣 Feedback](#-feedback)
* [©️ Legal](#️-legal)


## 📝 Description

This is a repackaging of the compiled iOS module for [ti.coremotion](https://github.com/appcelerator-modules/ti.coremotionn) to allow for installation via npm.

## 🚀 Getting Started

### Install `@titanium/coremotion` in root of project

```bash
npm install @titanium/coremotion
```


#### Example

```js

var coreMotion = require('@titanium/coremotion');

var accelerometer = coreMotion.createAccelerometer();
var gyroscope = coreMotion.createGyroscope();
var magnetometer = coreMotion.createMagnetometer();
var deviceMotion = coreMotion.createDeviceMotion();
var motionActivity = coreMotion.createMotionActivity();
var pedometer = coreMotion.createPedometer();

```

## ✨Features

* [x] Includes Titanium native iOS module: `ti.animation 2.0.0`
* [x] Includes Titanium native Android module: `ti.animation 3.0.0`
* [x] Display Lottie animations

## Library versions:

The Titanium modules use external libraries

|Library|Platform|Version|Build Date|
|---|---|---|---|
| [Airbnb Lottie](https://github.com/airbnb/lottie-android) | Android | 2.6.1 | 2018/09/06 |
| [Airbnb Lottie](https://github.com/airbnb/lottie-ios) | iOS | 2.5.2 | 2018/12/10 |





## 📚Learn More

- [Ti.Animation GitHub Repo](https://github.com/m1ga/ti.animation) - Repo for Ti.Animations modules
- [LottieFiles](http://www.lottiefiles.com/) - Free Lottie animations


## 📣 Feedback

Have an idea or a comment?  [Join in the conversation here](https://github.com/brentonhouse/titanium-lottie/issues)! 

## ©️ Legal

Modules are licensed under Apache 2.0 from https://github.com/appcelerator-modules/titanium-lottie

Alloy is developed by Appcelerator and the community and is Copyright © 2012-Present by Appcelerator, Inc. All Rights Reserved.

Alloy is made available under the Apache Public License, version 2. See their license file for more information.

Appcelerator is a registered trademark of Appcelerator, Inc. Titanium is a registered trademark of Appcelerator, Inc. Please see the LEGAL information about using trademarks, privacy policy, terms of usage and other legal information at http://www.appcelerator.com/legal.