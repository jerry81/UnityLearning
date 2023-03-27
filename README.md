# UnityLearning

## pricing

- unity has several tiers
  - split into individual, teams, enterprise
  - individual have two "free" tiers - student, and personal.

- to deploy to multiple platforms, we need unity pro
- ar development (unity mars) also requires it
- havok physics engine

## getting started

1.  dl unity hub
2.  choose unity version
3.  onboard

## unity hub

- manages installations of unity editor
- place to create projects

- after making account, it asks me to install unity editor
- installing unity license for personal edition

- 4 tabs: projects, installs, learn, community

- on the learn tab there is a "publish your first mobile runner game" tutorial

- through hub, installed unity editor and webgl support

- project -> new has some templates, 2d platformer, lego, fps, karting

- trying 2d platformer

# learn

## unity essentials

- course, unity essentials
- install unity hub and editor
- microgames tutorials
  - unity editor opens


## unity editor

- unity editor itself has tutorials built in.
- trying side scroller tutorial

- feature 1 - play tester
  - enter play mode by hitting the play button
  - hit play again to exit

- hierarchy
  - folder structure that contains samplescene which has objects like player, enemies, camera, gamecontroller
  - visual ui to edit properties of objects like player

- debug loop - edit and play the game again, yes the character moves very fast now

- hand tool - navigate around the scene

- move tool - reposition stuff

- frame tool - zooms into a selected object

- drag enemy prefab (template for game object) into scene

- scale and rotate the enemy

- build and publish
  - webgl publisher - publish menu item
  - builds to local folder
  - takes quite some time
  - puts the game on the website
    - add a thumbnail
    - add a gameplay preview video by playing the game

# analyze what's in a unity project

## folder structure

- languages
  - Shaderlab (decl language specific to unity)
    - for shaders
    - "regular HLSL/Cg shading language"
    - file extension .shader
  - C#
  - HLSL
    - High level shader language - C-like language used with programmable shaders in DirectX
- Assets
  - Audio
    - wavs and wav.meta
  - Character
    - has some .meta files
      - all meta files look like yaml
    - animations subfolder
      - has .anim files
      - has .anim.meta files
      - has .controller file
      - .controller.meta
    - sprites subfolder
      - .png and .png.meta files
      - the pngs contain multiple images representing the object in different states
  - Environment - two folders with png and their metadatas
    - sprites
    - tiles
  - Mod Assets
    - has prefabs
      - more yml files
    - fonts
      - also yml
    - materials (.mat)
  - Scenes
    - .unity (yml) - very long, 200K lines long
    - .unity.meta
    - .lighting
    - .lighting.meta
  - Scripts - home of the .cs files
    - using UnityEngine;


- Library
  - i guess this is all the unity stuff placed into the project
- Logs
- Packages
- ProjectSettings
- Temp
- UserSettings
- WebGL Builds

# links

- [getting started with game development](./g4g.md)