# Stellaris-ModSync
A tool to ease the annoying process of getting all the mods right for a multiplayer game.

# What is it?
The Stellaris ModSync tool allows users to easily synchronize their mods with each other. I created the tool beacuse whenever I wanted to start a modded Multiplayer there was always someone with a missing mod and it took us ages to figure out who had a wrong or missing mod.

# How to use?
Simply run the .exe file as it requires no installation.
You can either manually type in the path of your settings.txt file or click the handy-dandy little "search" button that opens up a file prompt. Simply navigate to the file and select it (Usually located at C:\Users\<Username>\Documents\Paradox Interactive\Stellaris\settings.txt)
You then paste in the mod configuration in the large text box and hit the "Synchronize Mods" button. You need to agree to the risk that the tool might brick your settings file first by checking the check box next to it.

# How does the shareable format look like?

```
last_mods={
    "mod/ugc_[NUMBERS].mod"
    "mod/ugc_[NUMBERS].mod"
    ...
}
```
Just like that! I will implement a feature to easily generate those in a future version, but for now you just have to copy it directly from your settings.txt file.

# I have a brilliant idea for that tool!/I found a bug!
Cool! Just message me on discord `(lurts#1162)` and we can discuss it!

# Can you implement ...?
It depends. I develop this in my free time as I am still in school and have very little experience with C# so far. I will most likely look into it but I can't promise anything yet.

# Disclaimer
The Tool is entirely developed my me, a rather unexperienced programmer who is still learning C#, so you might encounter some major bugs or errors. If you find one feel free to message me like above. I take no responsibility for any damage this tool might have caused to your Game or Computer (even thoug the latter is pretty unlikely).
