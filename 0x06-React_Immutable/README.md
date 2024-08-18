In object-oriented (OO) and functional programming,
an immutable object (unchangeable object) is an object whose state cannot be modified after it is created.
This is in contrast to a mutable object (changeable object), which can be modified after it is created.
In some cases, an object is considered immutable even if some internally used attributes change,
but the object's state appears unchanging from an external point of view.
For example, an object that uses memoization to cache the results of expensive computations
could still be considered an immutable object.

Strings and other concrete objects are typically expressed as immutable objects
to improve readability and runtime efficiency in OO programming.
Immutable objects are also useful because they are inherently thread-safe.
Other benefits are that they are simpler to understand and reason about and offer higher security than mutable objects.
