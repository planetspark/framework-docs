# Quick start

Use the following steps to easily create a game.

## Download this repository

This repository contains the basic template for game creation.

URL - [Template](https://github.com/docsifyjs/docsify/#showcase)

* **assets** - Folder holding all the aseets.
  * *images*
  * *audio*
  * *spritesheets*
* **config** - contains game config file and font files.
* **views** - contains all the screens of a game.
* *game.js* - main game file.
* *index.html* - main html file.

## Assets Folder

After cloning the above repository move all your assets to the `assets` folder.

* Images in `images` folder
* Audio in `audio` folder

Run the assets.sh script present in the assets folder to create a Asset Manifest File. Phaser scans this file and loads all the assets.

## Scene Creator

Create Scenes using the following scene creator. 

URL - [Scene Creator](https://github.com/docsifyjs/docsify/#showcase)

After Creating the scenes submit and download scenes.

## Add Logic and Animation

After creating scenes add logic by defining callbacks to different objects defined. Also add initial animtaion for objects. Refer to the documentation for different objects.

## Final Steps

These are the final steps - 

* Push data for different events. Refer the Events section for all type of events.
  * [Events](/events.md)
* Call these functions before anytime closing the game - 
  ```
    window.OUTDATA.setData(window.EVENTS.all());
    window.OUTDATA.closeGame();
  ```

