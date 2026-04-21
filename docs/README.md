<div align="center">
  <img src="https://github.com/user-attachments/assets/cd77f301-9024-4ba9-9364-76ad96243517"/>

  <b>An ImGui library for Roblox that doesn't require a RenderStep connection.</b>
  <br/>
  Perfect for beginners and performance.
</div>

## Screenshots
<table>
	<tr>
		<td width="600">
			<img src="https://github.com/user-attachments/assets/ce35cbdc-4b72-490c-af93-0c3aa6ee5c21" height="100%">
		</td>
		<td width="600">
			<img src="https://github.com/user-attachments/assets/e70800bf-b868-43f5-ba0a-9e3ac7a47a56" height="100%">
		</td>
	</tr>
</table>


## Notices❗
- This UI library is in beta, please report any bugs by opening an issue
- Any feedback or suggestions would be great
- Please mention me when integrating this library **- depso.**

## Usage and documentation
For **documentation** and usage examples, please read the [**Wiki**](https://github.com/RiseBlox/Roblox-ImGUI/wiki)

<table>
  <tr>
    <th>Type</th>
  </tr>
  <tr>
    <td>Roblox Studio</td>
    <td>
	    
If you would like to use this in Studio:
- Create a module script and paste the [library source code](/ImGui.lua)
- Download the [Prefabs UI](https://create.roblox.com/store/asset/85607317875581) and insert the ScreenGui it under the module script

```lua
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local ImGui = require(ReplicatedStorage.ImGui)
```

</td>
  </tr>
  <tr>
    <td>Exploit/Executor</td>
    <td>
	    
Reference detections have been mitigated using **cloneref** which compatibility is checked, \
if support is not found, for example using this in _studio_, you are still able to use it. 

```lua
local ImGui = loadstring(game:HttpGet('https://github.com/RiseBlox/Roblox-ImGUI/raw/main/ImGui.lua'))()
```

</td>
  </tr>
</table>

## Forking this
If you would like to create your own version for whatever reason,
- Prefabs: [Prefabs](https://create.roblox.com/store/asset/85607317875581)
- - Make sure you change UIAssetId under the `ImGui` configuration inside of the source code
- Library: [Source code](/ImGui.lua) 


## Demos/Usage examples
- The **demonstration window** can be found [here](/Demo%20window.lua)
- More usage examples can be found on the [Wiki](https://github.com/RiseBlox/Roblox-ImGUI/wiki)
