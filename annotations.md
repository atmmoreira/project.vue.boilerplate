# Learning React from Book React Beginning Foundations

- React.render() - create the output of a components.
- ReactDOM.render() - the output to be displayed in the browser. Its a method creates a lightweight and simplified representation of the React element in memory (this is the VirtualDOM).
- The ReactDOM library compares the new Virtual DOM representation of the web page to
the previous Virtual DOM representation and calculates the difference between the two. This
process is called `reconciliation`.
- ReactDOM applies just the minimal set of changes to the browser DOM in the most efficient
way that it can and using the most efficient batching and timing of changes.
- continue page 75