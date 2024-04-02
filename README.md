# Nodini
A humble little node-based program for visualizing and managing one-liners. Targeted towards bug hunters, pentesters, and lovers of automation.
---
<img width="862" alt="Overview" src="https://github.com/GerhardBotha97/Nodini/assets/53526803/cd668ce4-8e83-480d-b0fa-766141653b06">
---
## Usage:
It's pretty point-and-click, the following buttons on the graph are responsible for the following:
- Add: Add a Node
- Build: Build your playbook
- Save: Save the playbook to a template file to share or work on later
- Load: Load the template file into your graph
- Clear: Clear all
- Runner's Clear: Clear the runners
- Environment Variables' Clear: Clear the variables


## Node Buttons:
  The node consists of three parts:
- Text Field: Input your commands
- Separator dropdown: Select your separator
- X Button: Remove the individual node from your graph


## Environment Variables:
  1. To use them, place the variable you want between single underscores eg `_Secret_`.
  2. When you Build the playbook, it should appear, and you can enter whatever value you want.
  3. If it is a secret, you can hide it with the checkbutton.


## Runners
- If you wish to share a one-liner without the secret, choose `Copy`.
- If you want to run it, choose `Run`. Note that this will replace the Variable Name with whatever is in the Value!
