## Welcome to ProjectAqua

ProjectAqua is an robotic, mechanical, program and game engine that handles multiple programming languages in one file..
For example, if you want to merge Lua and C++, no problem, our engine will allow you to communicate through different programming languages with ( for example ) 2 files. Not only the coding experience is innovative and eased but it'll be a great step for the future. ProjectAqua can create wonderful futuristic masterpieces, from games to VR Realism Simulation.

ProjectAqua also has a Built-In Programming Languages Merging Classes ( unite, goback, loadfile, loadsinglestring )

## Lua to C++ Example
```lua
local FileLocation = {"/Workspace/Engine/VR", "/Workspace/Engine/CodeAssets", "/Workspace/Server/Scripts"}
local ignored = {"/Workspace/Unused", "/Workspace/Engine/Unused/", "/Workspace/Engine/CodeAssets/handling.lua", "/Workspace/Server/Scripts/Unused"}

loadfile('/Workspace/Engine/CodeAssets/C++/main.cpp')

from loadfile:LoadPreviousFile:GetString(1, 10 ) -- 1, 10 = from String 1 ( Start ) to String 10 ( End )
-- Lua to C++ Example
```
## Java to C++ Example
```java
string Workspace = "/ExamplePathStart/Workspace"
string Server = "/ExamplePathStart/Workspace/Server"
string EngineMain = "/ExamplePathStart/Workspace/Engine"

public class Loading {
  loadfile(Workspace)
  getFile(Workspace .. '/C++/main.cpp')
}
```
## What Programming Languages does ProjectAqua Support?
ProjectAqua supports every non-web related programming languages ( html, php, and sql [partially] are not supported ).
## Can i Download ProjectAqua?
No, ProjectAqua is not ready to be public yet, however we are gonna publish some code on our main repository. Thanks for reading and Bye!
