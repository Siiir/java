# My projects using Java


#### See my related hard skills
[C#](https://github.com/Siiir/csharp)


## Contents

### [licensing service](https://github.com/Siiir/java-licensing-service) on Spring Boot
Allows creation, reading, update, deactivation of licenses.
All licenses created for customers are based on the root "buyable license" and contain additional owner-specific info.

### [Chat server](https://github.com/Siiir/java-ChatServer) on Spring Boot
Serves chat messages to all chat clients that request them. Allows clients to post new messages and efficiently ping to see if a new message was posted.

### [CanvEngine](https://github.com/Siiir/CanvEngine) on Swing
Game engine using CPU-based rendering on `JPanel`.
#### Etymology
In "Canv-Engine" the "Canv" stands for "Canvas", that is because `JPanel` serves the role of "Canvas" in graphics rendering.
#### Examples of usage
In the `examples` submodule **you can find some games and simulations** made using this engine.

There is a notable **`plain_tanks`** game that is **not fully using CanvEngine** as it was only partially-ported from my first (integrated) Java game engine to *CanvEngine*. I only found time to make *Plain Tanks* use CanvEngine's asset server instead of old one that really didn't have a good support for caching sounds.
