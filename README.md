# NeuronDotNet

## Why?
I wanted to play with neural network in Unity and that was the only library I found that I could make it work with Unity.

## What?
This is a neural network library that work in Unity.  
The original source code is located at sourceforge.net, but it looks like it has not been touch since 2008.  
However, it seems to work!  
Original Source : https://sourceforge.net/projects/neurondotnet/

## How?
I just had to refactor some data structures to use the ones available in the .Net 2.0 SubSet.
I think I made some additions to the library so that I could call certain methods in the Unity game loop.

## Usage Examples
I have some Unity projects using this library:  
https://github.com/tiagosomda/NeuralGames

### How to include in your Unity project?
Just download the library, build it, copy/paste the output dll (NeuronDotNet.Core.dll) under the Assets/Library folder in your Unity project. Call the library as you would with any other class.

### Documentation
The only thing close to a documentation right now are the examples and the source code itself.

## Why not other libraries?
I am sure there are ways to run TensorFlow, CNTK, AForge.Net in Unity, but I haven't had time to explore these paths...  

LEt me know if you do know how to use other (more recent or better supported) libraries :)  

CNTK: https://github.com/Microsoft/CNTK   
TensorFlow: https://www.tensorflow.org/  
AForge.Net : http://www.aforgenet.com/  
