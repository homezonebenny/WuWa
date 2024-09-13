URL:
https://www.nexusmods.com/wutheringwaves/mods/17


1. Copy Engine.ini and Scalability.ini into:
..Wuthering Waves\Wuthering Waves Game\Client\Saved\Config\WindowsNoEditor


2. Copy ~mods folder into:
D:\Games\Wuthering Waves\Wuthering Waves Game\Client\Content\Paks


3. If you want to play in "Fullscreen" instead of "Windowed" mode edit this file:
.\Wuthering Waves Game\Client\Content\Paks\~mods\Config\WuWa-Tweaks.json
Change the value to:
"borderless": false,




# ATTENTION: The last step is optional!
# When I play the game with the extra shortcut I get a "memory overload" of the graphic card after ~15min...
# Or when I use the menus to often...
# To fix this you need to play the game with DX11 instad of DX12
# Or just start the game via the normal shortcut to this Path:
# .\Wuthering Waves\Wuthering Waves Game\Wuthering Waves.exe
# I use a RTX 4070 and it seems like the 40x Series of nVidia have this issue with the Engine.ini settings + DX12
# Just skip the 4. point if you have trouble!


4. Create a new shortcut:
D:\Games\Wuthering Waves\Wuthering Waves Game\Client\Binaries\Win64\Client-Win64-Shipping.exe
Add a:
-fileopenlog
to the "Target" path of the shortcut, like this example:
"D:\Games\Wuthering Waves\Wuthering Waves Game\Client\Binaries\Win64\Client-Win64-Shipping.exe" -fileopenlog