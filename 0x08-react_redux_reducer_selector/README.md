Redux is a pattern and library for managing and updating global application state,
where the UI triggers events called "actions" to describe what happened,
and separate update logic called "reducers" updates the state in response.
It serves as a centralized store for state that needs to be used across your entire application,
with rules ensuring that the state can only be updated in a predictable fashion.

Why Should I Use Redux?
Redux helps you manage "global" state - state that is needed across many parts of your application.

The patterns and tools provided by Redux make it easier to understand when, where, why,
and how the state in your application is being updated,
and how your application logic will behave when those changes occur.
Redux guides you towards writing code that is predictable and testable,
which helps give you confidence that your application will work as expected.

When Should I Use Redux?
Redux helps you deal with shared state management, but like any tool, it has tradeoffs.
There are more concepts to learn,
and more code to write.
It also adds some indirection to your code,
and asks you to follow certain restrictions.
It's a trade-off between short term and long term productivity.

Redux is more useful when:

You have large amounts of application state that are needed in many places in the app
The app state is updated frequently over time
The logic to update that state may be complex
The app has a medium or large-sized codebase, and might be worked on by many people
Not all apps need Redux.
Take some time to think about the kind of app you're building,
and decide what tools would be best to help solve the problems you're working on.

Want to Know More?
If you're not sure whether Redux is a good choice for your app, these resources give some more guidance:

When (and when not) to reach for Redux
The Tao of Redux, Part 1 - Implementation and Intent
Redux FAQ: When should I use Redux?
You Might Not Need Redux
Redux Libraries and Tools
Redux is a small standalone JS library. However, it is commonly used with several other packages:

Redux Toolkit
Redux Toolkit is our recommended approach for writing Redux logic.
It contains packages and functions that we think are essential for building a Redux app.
Redux Toolkit builds in our suggested best practices, simplifies most Redux tasks, prevents common mistakes,
and makes it easier to write Redux applications.

React-Redux
Redux can integrate with any UI framework, and is most frequently used with React.
React-Redux is our official package that lets your React components interact with a Redux store
by reading pieces of state and dispatching actions to update the store.

