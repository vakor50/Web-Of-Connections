# Web of Connections

Using the UI, a user can create a web of connections.

## Planned Enhancements

Editing added nodes and their children
- Implement state management so that you can click an added node from the web and it will be loaded into the input boxes for editing
- Need to be aware that editing could break other connections so might be better to only make delete an option


## Version 3

Setup for real world application (Wikipedia)
- Use Wikipedia API (MediaWiki) so you can make a web of links off a wikipedia page
- First run loads all external links (Ext)
- Second and future runs load  external links from Ext and creates connections between pages that link to each other (doesn't run on non-wikipedia external links for simplicity)

## Version 2

Nodes have a delete button such that it and it's children are removed from the graph.
Any other node that references the deleted node or its children will still remain.

Give more details about connections
- Add ability to add a description to a connection
- For PA <--> MD, the edge could have custom text saying something like 'Adjacent US States' 

## Version 1

Note: Each node must have a unique name becuase nodes and their children are connected via the name

1. Enter the parent node's name
2. Add the parent node's direct children via the list of input boxes
3. Click 'Add Node' to add that node
4. Repeat to add more nodes
