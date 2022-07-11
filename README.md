# DaVinci-Resolve

Davinci Resolve Development

This is the GitHub repository for the new 2022 Resolve Development.

A Snippet in VS Code is a shorthand keyword or letter combination followed by pressing the tab key, this will then insert the appropriate snippet. Please read more about creating snippets here to further understand their use. https://code.visualstudio.com/docs/editor/userdefinedsnippets

DaVinci Resolve .setting files are written in lua a fast, human readable programing language. In a Macro there are several sections to the code.

Inputs, these are the controls you see in the inspector
Outputs, this is usually the last node in the node tree before the MediaOut node.
Tools, these are the actual nodes

The code snippet is the basic working code to get you going, think of it as a template, the cursor will be located where a user input is required and tab will move to the next input required.

As an example to add a drop down menu (label) to the inspector you a required to add code in both the input section of the code and the tool section of the code.

Version 1.0.0 VSCode Snippets for DaVinci Resolve
Key combination{"l" followed by "Tab"}
Result = Basic code for a label.

{"l" "tab"} = inspector (input) Label
{"nl" "tab"} = node (tool) Label
{"nol" "tab"} = inspector (input) Note
{"nn" "tab"} = node (tool) Note
{"rl" "tab"} = inspector (input) Range Tool
{"ra" "tab"} = node (tool) Minimum and Maximum Range
{"crl" "tab"} = inspector (input) Row of 3 Checkboxes
{"cr" "tab"} = node (tool) Row of 3 Checkboxes
{"btl" "tab"} = inspector (input) MultiButton
{"bt "tab"} = node (tool) Template for 4 Buttons as a MultiButton
{"ls" "tab} = inspector (input) Slider
{"bs" "tab"} = node (tool) Slider
{"ms" "tab"} = inspector (input) Mix Slider
{"mxs" "tab"} = node (tool) Mix Slider
{"ltc" "tab"} = inspector (input) Tristate Checkbox
{"cb" "tab"} = node (tool) Tristate Checkbox
{cd" "tab"} = CustomData url no longer applicable
{"ucs" "tab"} = node (tool) User Control Text Box
{"st" "tab"} = Text Node (tool) code to customize a text box height
{"uc" "tab"} = node (tool) UserControl section in a node
{"p" "tab"} = inspector (input) add page option to a control
{"n" "tab"} = inspector (input) add a name option to a control
{"btn" "tab"} = inspector (input) button to url
{"nbtn" "tab"} = node (tool) add a button for a url
{"com" "tab"} = node (tool) add a user comment
{"lbtn" "tab"} = inspector (input) preset button
{"pbtn" "tab"} = node (tool) preset button
