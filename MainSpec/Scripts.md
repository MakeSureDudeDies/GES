# Scripts

The **Script** library will be useful to interact with Roblox scripts. 
---
## getscriptbytecode

Returns bytecode of a script. The only argument here is the script path.

Usage:

```lua
print(getscriptbytecode(workspace.SomeScript))
```
---
## getscripts

Returns a table with every LuaScriptContainer instance (even the ones parented to nil)

Usage:

```lua
for i, v in pairs(getscripts()) do
print(v.Name)
end
```
---
