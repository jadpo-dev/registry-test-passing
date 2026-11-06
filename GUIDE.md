# Initials

A test fixture for the jadpo.dev package registry's staging environment. It isn't meant for use.

Call `Initials.initials.of(name)` with a name as someone typed it, or `Initials.initials.dotted(name)` for initials
with full stops. Each gives the first letter of each word in capitals, and fails with `NoName` when the name holds
only spaces.
