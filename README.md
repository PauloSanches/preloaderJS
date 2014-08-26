PreloaderJS [![Build Status](https://travis-ci.org/PauloSanches/preloaderJS.svg?branch=master)](https://travis-ci.org/PauloSanches/preloaderJS)
==========

javascript library for prelaod images

## Getting Started
Just create an instance of PreloaderJS and pass params
````js
var preloader = new snch.PreloaderJS(['ui_sprite.png','logo.jpg','social_sprite.png'], onComplete);

function onComplete(data) {
  // dependencies loaded
}
````

## Params

| Parameter     | Description       |
|---------------|-------------------|
| dependencies      | Array of dependencies     |
| callback      | Function  return dependencies loaded   |
