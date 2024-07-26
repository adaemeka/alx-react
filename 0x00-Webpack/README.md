Nowadays, we’re forced to use many accessory tools to facilitate,
speed up and optimize our web development workflow.
Often, though, such tools add an extra layer of complexity into the stack.
As a result, we need to utilize additional time and effort to learn,
understand and use these tools correctly. The same is true for webpack.

When using webpack for the first time,
it can be difficult to understand how it works and how it should be used.
Although it has good documentation,
it can be daunting for novices, and it has a steep learning curve.
However, webpack is worth learning and can save considerable time and effort in the long run.

What Is Webpack?
As its core, webpack is a static module bundler.
In a particular project, webpack treats all files and assets as modules.
Under the hood, it relies on a dependency graph.
A dependency graph describes how modules relate to each other using the references
(require and import statements) between files.
In this way, webpack statically traverses all modules to build the graph,
and uses it to generate a single bundle (or several bundles) —
a JavaScript file containing the code from all modules combined in the correct order.
“Statically” means that, when webpack builds its dependency graph,
it doesn’t execute the source code but stitches modules and their dependencies together into a bundle.
This can then be included in your HTML files.
