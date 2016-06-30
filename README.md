# SmearFrame
"Smear frame" material effect for Unreal Engine 4.12

![Smear Frame effect](http://broad-strokes.com/media/smear3.gif "UE4 Smear Frame effect")

## What is this?
This is an Unreal Engine 4 project containing a simple implementation of a "smear frame" effect, as recently popularized by the game Overwatch.

## How do I use this?
This effect consists of two parts: a blueprint component you add to an actor you want to be affected by the smear frame effect, and a material function that you add to its material.

## Limitations
As a quick and dirty proof of concept, this effect uses the actor's velocity to determine smear strength. As such, it does not work with animated skeletal meshes in the way you'd expect. Suggestions or pull requests are very welcome though! :)

![Smear Frame effect](http://broad-strokes.com/media/smear.gif "UE4 Smear Frame effect")

## Credits
Created by Jan Kaluza of [Broad Strokes](http://www.broad-strokes.com) ([@JKashaar on Twitter](https://twitter.com/JKashaar)).

Inspired by Blizzard's Overwatch, as well as Twitter user [@MercurialForge](https://twitter.com/MercurialForge/status/747871518575648768)
