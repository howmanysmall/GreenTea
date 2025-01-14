# Changelog

## Unreleased

Nothing yet!

## 0.4.6

- Fix buggy type definition for `GreenTea.fn`
- Make `GreenTea.build` handle tuples properly
- Export a type for `GreenTea.build`'s "BuiltType" values

## 0.4.5

- Fix type signature of `__call`
- Fix typechecking failure in `.meta`

## 0.4.4

- Fix: meta did not return input

## 0.4.3

- Add `meta` to exports

## 0.4.2

- Make metadata type more permissive

## 0.4.1

- Add user-specified metadata

## 0.4.0

- Change behavior around tables to respect `__iter`, `__index`
- Change behavior around tables to not check if ``getmetatable(input) == getmetable(typedef)`

## 0.3.1

- Only show simplified input types in error messages

## 0.3.0

- Change `Type.__call` to return a string cause instead of an object for `t` and `assert` compatibility.

## 0.2.1

- Add missing `t` members

## 0.2.0

- Catch edge case where a GreenTea constructor is passed into a GreenTea constructor
- Freeze GreenTea and its child tables so they can't be modified
- Change `basic` types to have a `typeof` or `type` to differentiate them _[breaking change]_
- Fix some docs issues

Pushing this is a normal breaking change because no one's using this library yet so there are no ecosystem concerns about a breaking change!

## 0.1.1

- Fixed formatting for error cases where 3+ errors occur on one line.

## 0.1.0

Initial release.
Expect future breaking changes as ergonomics are figured out.