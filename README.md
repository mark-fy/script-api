# TopHat Scripting API
## Functions
### onEnable
```lua
function onEnable()
    -- Perform initialization tasks here
end
```
### onDisable
```lua
function onDisable()
    -- Perform simple closing tasks here
end
```
## Methods
### Chat Methods
```lua
chat:print("message") -- prints to the ingame chat
```
### Player Methods
```lua
player:setSpeed(doubleValue) -- sets the player's speed
player:setX(doubleValue) -- sets the player's X position
player:setY(doubleValue) -- sets the player's Y position
player:setZ(doubleValue) -- sets the player's Z position
player:setPitch(floatValue) -- sets the player's rotation pitch
player:setYaw(floatValue) -- sets the player's rotation yaw
player:setMotionX(doubleValue) --  sets the player motion x value
player:setMotionY(doubleValue) -- sets the player motion y value
player:setMotionZ(doubleValue) -- sets the player motion z value
player:setGround(doubleValue) -- sets the player's onground value
player:setSprint(booleanValue) -- sets the player sprinting
player:jump() -- makes the player jump once
player:swing() -- swings the player's hand once
```
