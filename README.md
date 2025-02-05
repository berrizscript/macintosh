Welcome to the Macintosh UI Library!

this readme file will help you operate this ui library for your own use!

Develop Progress: 
Alpha Test
# How to use the ui!

- To start, you will need to add the configure loadstring!

 this configure file stores the gui for later use.
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/berrizscript/macintosh/refs/heads/main/configure"))()
```

- After, you will need to *load* the window, using this code block!

This loads the window to start the gui!
```lua
local Window = Library:CreateWindow("Untitled Window")
```
^ Change ”Untitled Window” to your selected name.

- Now that the window and configuration scripts are loaded, you need to add tabs to add elements!

This creates the tab with the name as Untitled
```lua
local UntiitledTab = Window:CreateTab("Untitled")
```
fyi, you need to change the name, otherwise it will mess up other tabs.
Example:
`local OtherTab = Window:CreateTab("hello")`
name should not interfere with other tabs (same name) but name in gui can be the same as a othee tab name in gui aswell

- Elements

Here are all the elements you can put in a tab, make sure you make it the same name!


