[//]: # (header-start)

<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<h1 align="center">
	🪦 RIP Axway Amplify Titanium (2010 - 2022)
	</h1>
</a>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		<img src="https://cdn.secure-api.org/images/RIP-Axway-Amplify-Titanium.png" alt="RIP Axway Amplify Titanium (2010 - 2022)" width="80%" />
	</p>
</a>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		🪦 &nbsp; RIP Axway Amplify Titanium (2010 - 2022)
	</p>
</a>
<p>&nbsp;</p>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<h2 align="center">
		🛑 This project is no longer being maintained 🛑
	</h2>
</a>
<p>&nbsp;</p>
<hr>
<p>&nbsp;</p>
<p>&nbsp;</p>

[//]: # (header-end)



# @titanium/coremotion

[![@titanium/coremotion](https://img.shields.io/npm/v/@titanium/coremotion.png)](https://www.npmjs.com/package/@titanium/coremotion)
[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=brentonhouse/titanium-coremotion)](https://dependabot.com)

> This is an experiment by [Brenton House](https://brenton.house) using open-source projects.  You are welcome to try it out but be aware of the risks_

<br/>

* [📝 Description](#-description)
* [🚀 Getting Started](#-getting-started)
	* [Install `@titanium/coremotion` in root of project](#install-titaniumcoremotion-in-root-of-project)
		* [Example](#example)
* [✨Features](#features)
* [📚Learn More](#learn-more)
* [📣 Feedback](#-feedback)
* [©️ Legal](#️-legal)


## 📝 Description

> Native modules that allows you to use iOS CoreMotion framework with Axway Titanium native mobile apps.
>    
> This is a repackaging of the compiled iOS module for [ti.coremotion](https://github.com/appcelerator-modules/ti.coremotion) to allow for installation via npm.

## 🚀 Getting Started

### Install `@titanium/coremotion` in root of project

```bash
npm install @titanium/coremotion
```


#### Example

```js

const coreMotion = require('@titanium/coremotion');

const accelerometer = coreMotion.createAccelerometer();
const gyroscope = coreMotion.createGyroscope();
const magnetometer = coreMotion.createMagnetometer();
const deviceMotion = coreMotion.createDeviceMotion();
const motionActivity = coreMotion.createMotionActivity();
const pedometer = coreMotion.createPedometer();

```

## ✨Features

* [x] accelerometer
* [x] gyroscope
* [x] magnetometer
* [x] deviceMotion
* [x] motionActivity
* [x] pedometer
* [ ] altimeter



## 📚Learn More

⭐  [ti.coremotion GitHub Repo](https://github.com/appcelerator-modules/ti.coremotion) - Repo for ti.coremotion modules   
⭐  [Apple iOS CoreMotion](https://developer.apple.com/documentation/coremotion?language=swift)    


## 📣 Feedback

Have an idea or a comment?  [Join in the conversation here](https://github.com/brentonhouse/titanium-lottie/issues)! 

## ©️ Legal

Modules are licensed under Apache 2.0 from https://github.com/appcelerator-modules/titanium-lottie

Alloy is developed by Appcelerator and the community and is Copyright © 2012-Present by Appcelerator, Inc. All Rights Reserved.

Alloy is made available under the Apache Public License, version 2. See their license file for more information.

Appcelerator is a registered trademark of Appcelerator, Inc. Titanium is a registered trademark of Appcelerator, Inc. Please see the LEGAL information about using trademarks, privacy policy, terms of usage and other legal information at http://www.appcelerator.com/legal.