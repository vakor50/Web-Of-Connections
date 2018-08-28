# Web of Connections

Using the UI, a user can create a web of connections.

## Planned Enhancements

Editing added nodes and their children
- Implement state management so that you can click an added node from the web and it will be loaded into the input boxes for editing
- Need to be aware that editing could break other connections so might be better to only make delete an option

Give more details about connections
- Add ability to add a description to a connection
- For PA <--> MD, the edge could have custom text saying something like 'Adjacent US States' 

Setup for real world application
- Acquire access to some Wiki API so you can make a web of links off a wikipedia page
- First iteration loads all external links (Ext)
- Second iteration loads all external links from Ext and creates connections between pages that link to each other (doesn't run on non-wikipedia external links for simplicity)

## Version 1

Note: Each node must have a unique name becuase nodes and their children are connected via the name

1. Enter the parent node's name
2. Add the parent node's direct children via the list of input boxes
3. Click 'Add Node' to add that node
4. Repeat to add more nodes
