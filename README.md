# <img src="https://github.com/specialman39824/test/blob/main/contents/animationwrapper.png" width="48"/> Animation Wrapper

[![File](https://img.shields.io/badge/get-File-blue
)](https://github.com/specialman39824/test/raw/main/Animation.rbxm)

* A simple to-use script that loads and plays any available animation in any Roblox game without needing to upload it. The script required KeyframeSequence to load/play animations.
This works both in studio and live. 

> [!NOTE]
> The animation will be loaded via KeyframeSequence Only.

# USAGE:
```lua
local AnimationWrapper = require(path.to.here)

-- Example
local animationPlayer = AnimationWrapper.load(character, keyframeSequence, true)
animationPlayer:Play()

--AnimationWrapper.load(char: Model, anim: KeyframeSequence, noCache: boolean?) -> AnimPlayer

--AnimPlayer.Priority (number)
--AnimPlayer.Looped (boolean)
--AnimPlayer.Speed (number)
--AnimPlayer.UpdateMotor (function, can be overwritten)

--AnimPlayer:Play()
--AnimPlayer:Stop()
```

## Contributors
* [Parenthesis](https://twitter.com/ryokayaru) - Wrote the README.md page.
* [specialman39824](https://twitter.com/higuys2040) - Wrote this script.
