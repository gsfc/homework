# Tree Builder

###### In this exercise you'll show the ability to *GET* data from a server and format it into a tree structure.

###### Target Skills: Data Structures and Algorithms

###### Estimated Completion: 1-3 hours


\**This exercise requires node for running an express server and reading file data. 
If you do not have node install you can download [Node](https://nodejs.org/en/download/).*


## Your Job 
- `GET` the data at http://localhost:8080/data 
- Convert server data into a **Tree Data Structure** 
- Render tree with `renderTree( [tree-node(s)] );`


## Getting Setup
1. Download codebase
2. Open a terminal in this directory 
3. Type `npm install` - this installs the node dependencies for this exercise
4. Type `npm run start` - this runs your local server at http://localhost:8080/


## Notes
- All your code will be written the in `src/code.js` file
- Each node in your tree will be in the form `{ id: "id", text: "text", children: [] }` 
- To see a finished tree run `exampleTree()`
- To check you data structure is in the correct format run `testTree( [tree-node(s)] )`