# Commit Message Guidelines

Formatting commit messages leads to more readable messages that are easy to follow when looking through the project history.

## Message Format

```
<type>: short description (fix: #1234)

If a longer description is required,
it should be written in this field,
which is the body of the message.
```

## Type

It must be one of the following:

* **feature:** For new features.
* **fix:** For bug fixes.
* **style:** For UI/UX changes.
* **document:** To document the code.
* **test:** To add, delete, or update the tests of the code.
* **refactor:** For changes that neither fixes a bug nor adds a feature. Changes that do not affect the meaning of the code (white-space, formatting, missing semicolons, etc.) also should be evaluated under this type.

## Revert

If the commit reverts a previous commit, it should begin with `revert: `, followed by the header of the reverted commit.

In the body it should say: `This reverts commit <hash> .`  where the hash is the SHA of the commit being reverted.

## Subject

* Use the imperative, present tense.
* Do not capitalize the first letter.
* Do not use dot (.) at the end.
* If there is an issue, reference it at the end. If the commit does not completely fix the issue, then use `(ref: #1234)` instead of `(fix: #1234)`.

## Body

* Use the past tense in the passive voice.