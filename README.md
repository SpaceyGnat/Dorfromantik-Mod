# Dorfromantik-Mod
Its a Mod that changes the tiles gain from 4 to 54 in the game Dorfromantik.
Step 1: go to C:\SteamLibrary\steamapps\common\Dorfromantik\Dorfromantik_Data\Managed
Step 2: (optinal/recommended) make a backup up of the Assembly-CSharp.dll put it in a folder on your desktop or somewhere you can find it later.
Step 3: replace the Assembly-CSharp.dll file with the one you downloaded.
Step 4: Lunch the game.

for those wondering how i did this i use a tool called dnSpy its a decompiler use to mod unity games.
I found the this.AddRandomTiles(count, true); under the AddQuestRewardTiles event and modified it to this.AddRandomTiles(count + 50, true);
This is my first mod im not a expert im am also a noob at programming.
