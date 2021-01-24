[![Build Status](https://travis-ci.com/jcs090218/Unity_Toggle.svg?branch=master)](https://travis-ci.com/jcs090218/Unity_Toggle)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

# Unity Toggle #

A little bit overkill iOS style toggle button. 

## Usage ##
```cs
JCS_Toggle togBtn = this.GetComponent<JCS_Toggle>();

// Check if the toggle is on or off?
bool isOn = togBtn.IsOn;

// Toggle the button.
togBtn.Toggle();

// Set interactable.
togBtn.Interactable = !togBtn.Interactable;
```

## Screenshot ##
<img src="./screenshot/toggle_demo.gif"/>

## 3rd Party Source ##
* *JCSUnity* : https://github.com/jcs090218/JCSUnity by <a href="https://github.com/jcs090218">Jen-Chieh Shen</a>
* *Tweener* : https://github.com/PeterVuorela/Tweener by <a href="https://github.com/PeterVuorela">Peter Vuorela</a>

## Related Tool ##
* <a href="https://github.com/Kalxoznik/Unity-Toggle-controller">Unity-Toggle-controller</a> by <a href="https://github.com/Kalxoznik">Max Shakurov</a>
