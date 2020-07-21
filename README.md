# Server Utils

A C# library, along with a C++ helper dll, that will help you make game servers for games, preferable for Unity games.

## Why "preferable Unity games"?

I made this library with the knowledge I gained from making private servers for Monkey Quest and Battlestar Galactica Online, both Unity games. Because of that it contains scripts that were decompiled and/or adapted from Unity itself, allowing you to use Unity native code on the server (e.g. Quaternion).

## Why have closed source code?

In my opinion, some stuff shouldn't be open sourced, mainly Unity adaptations for closed source code from them. If you wish to have these closed source adaptations, you should be able to find it somewhere.

### Credits

- Unity
- BigPoint
- aeroson (For most of the implementation of UnityEngine.Quaternion)
- Florek (aka Mementomori)
