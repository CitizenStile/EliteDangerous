# EliteDangerous

Repository for Drait & CS to store their X56 HOTAS keybindings

Keybindings located at:
`%AppData%\..\Local\Frontier Developments\Elite Dangerous\Options\Bindings`

## Renaming keybindings files:
1. Within Elite Dangerous, click Options -> Controls -> General Controls
2. Identify which preset you are using (defaults to Keyboard & Mouse)
2a. If you have already renamed your keybinds file and the name inside the file, select that here and skip to ########
3. Close Elite Dangerous
4. Open the bindings folder listed above, and locate the file that coresponds to the in-game preset that is selected
5. Rename the file to **name**.4.0.binds (replace **name** with your character name)
6. Open the newly renamed file in text editor (Visual Studio Code is recommended)
7. On line 2 replace the PresetName with the character name you used to rename the file
7a. You can change MajorVersion to control which version of Elite the bindings are for
7b. 4 - Odyssey | 3 - Horizons
8. Save the file
9. Open Elite Dangerous, click Options -> Controls -> General Controls
10. Select the preset that corresponds to the name you entered in the previous steps
