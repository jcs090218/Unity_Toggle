[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Unity Engine](https://img.shields.io/badge/unity-2018.3+-black.svg?style=flat&logo=unity&cacheSeconds=2592000)](https://unity3d.com/get-unity/download/archive)

# Unity Toggle

[![Build Status](https://travis-ci.com/jcs090218/Unity_Toggle.svg?branch=master)](https://travis-ci.com/jcs090218/Unity_Toggle)

<img src="./screenshot/toggle_demo.gif"/>

A little bit overkill iOS style toggle button. 

## Usage

```cs
JCS_Toggle togBtn = this.GetComponent<JCS_Toggle>();

// Check if the toggle is on or off?
bool isOn = togBtn.IsOn;

// Toggle the button.
togBtn.Toggle();

// Set interactable.
togBtn.Interactable = !togBtn.Interactable;
```

## 3rd Party Source

* [JCSUnity](https://github.com/jcs090218/JCSUnity) by [Jen-Chieh Shen](https://github.com/jcs090218)
* [Tweener](https://github.com/PeterVuorela/Tweener) by [Peter Vuorela](https://github.com/PeterVuorela)

## Related Tool

* <a href="https://github.com/Kalxoznik/Unity-Toggle-controller">Unity-Toggle-controller</a> by <a href="https://github.com/Kalxoznik">Max Shakurov</a>
