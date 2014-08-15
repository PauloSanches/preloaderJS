PreloaderJS [![Build Status](https://travis-ci.org/PauloSanches/PreloaderJS.svg?branch=master)](https://travis-ci.org/PauloSanches/PreloaderJS)
==========

javascript library for prelaod images

## Getting Started
Just create an instance of PreloaderJS and pass params
````js
var preloader = new snch.PreloaderJS(['ui_sprite.png','logo.jpg','social_sprite.png'], onComplete]);

function onComplete(data) {
  // data is dependencies loaded
}
````

## Params

| Parameter     | Description       |
|---------------|-------------------|
| dependencies      | Array of dependencies     |
| callback      | Function  return dependencies loaded   |
