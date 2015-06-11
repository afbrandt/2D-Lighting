---
title: "Get started with this tutorial!"
slug: tutorial-page-1
---

Cocos2D continues to impress with a growing list of features.  With the release of Cocos2D 3.4 comes *CCLightNode* and the ability to easily add dynamic lighting to a scene.  SpriteBuilder 1.4 has integrated this feature and provides a real time preview.  This tutorial will introduce you to the steps required to include this in your next game.  Let's get started.

#Getting started

Let's make sure you have the right tools to make the lighting effects today.  You will need Xcode, of course.  Verify you have at least version 1.4 of SpriteBuilder.  This comes prepackaged with Cocos2D 3.4, so you're almost ready.  You need one more tool to generate normal maps for sprites that will have the lighting effects.

> [info] What's a normal map?
>
> A normal map is an image file that uses different colors to describe the surface of an object. Normal maps are used to simulate 3D effects, such as shadows or refraction of light on a sprite that is actually flat ([more info](http://en.wikipedia.org/wiki/Normal_mapping)).  
>

There is a tool that is currently free while its in beta, called CrazyBump.  Go ahead and download it [here](http://crazybump.com/mac/).  That's all you need!  Now to create the normal maps.

#Creating normal maps

Go ahead and fire up CrazyBump.  This tool automates most of the normal map generation, so there isn't much to do besides provide a source file.  Here's a quick walkthrough:

![](./CrazyBump.gif)

Feel free to experiment with the normal map sliders to observe how they influence the map.  We'll provide a couple assets and normal maps ([download here]()) or you can make your own.  Now you're ready to set the scene with SpriteBuilder.

#SpriteBuilder

1. create a new project
2. remove template elements
3. add assets to file view
4. drag image(s) onto timeline
5. add corresponding normal map
6. add lighting effect to ccsprite
7. add CCLightNode to timeline
8. explain different light types

#Xcode

With everything set up in SpriteBuilder, it is now time to add an interactive component.

#Finish
