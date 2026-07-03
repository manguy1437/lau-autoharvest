# lau-autoharvest
Plant With Coding script harvests whatever the drone is on when it can be harvested, script doesn't end until you stop it

```lua
varol hasLooped = false

while hasLooped == false do
while true do
if drone.canHarvest() then
	drone.harvest()
  hasLooped = true
end end end
```
hope this helped y'all
btw you can change the `drone.canHarvest()` and `drone.harvest()` to `drone.canCrop()`, and `drone.crop()` for plants like wheat
