# <img src="https://github.com/specialman39824/test/blob/main/animationwrapper.png" width="48"/> Animation Wrapper
[![File](https://github.com/specialman39824/test/blob/main/Animation.rbxm)

A script that loads and plays any available animation in any Roblox game without needing to upload it. The script required KeyframeSequence to load/play animations.
This works both in studio and live. 

> [!NOTE]
> The animation will be loaded via KeyframeSequence Only.

# DOCUMENT
```lua
local AnimationWrapper = require(path.to.here)

--AnimationWrapper.load(char: Model, anim: KeyframeSequence, noCache: boolean?) -> AnimPlayer

--AnimPlayer.Priority (number)
--AnimPlayer.Looped (boolean)
--AnimPlayer.Speed (number)
--AnimPlayer.UpdateMotor (function, can be overwritten)

--AnimPlayer:Play()
--AnimPlayer:Stop()
```
