# Agent Code Style Rules

Use this file as the formatting source of truth.
Do not invent missing rules.
Do not infer behavior from omitted items.
Do not merge `.editorconfig` rules into this spec.

## Global

- Do not enforce a maximum line length.
- Do not wrap text just because it is long.

## HTML

- Always quote attribute values.
- Do not wrap HTML attributes automatically.
- Do not wrap HTML text automatically.
- Do not force any specific HTML tags onto a new line before the opening tag.
- Do not exempt any HTML tags from child indentation.

## Markdown

- Do not hard-wrap paragraphs.
- Do not hard-wrap text inside blockquotes.

## JavaScript

- Write function declarations and function expressions with no space before `(`.
- Write async arrow functions with no space between `async` and `(`.
- Remove trailing commas.
- Do not wrap JavaScript variable declarations automatically.
- Do not wrap JavaScript object literals automatically.
- Always wrap ES module import or export lists.
- Do not add an extra indentation level only because a call is chained.
- Do not move the `.` of a chained call to the beginning of a new line.
- Normalize C-style comments when reformatting them.
- Do not force a space after `//` in line comments.
- Do not preserve existing line breaks during reformatting.
- Put `else`, `while`, `catch`, and `finally` on a new line.
- Use no space before the `(` in `if`, `while`, `for`, `catch`, and `switch`.
- Keep opening braces on the same line for block-level elements.
- Align multiline chained method or property calls.
- Keep simple blocks on one line when they fit.
- Always force braces for `if`, `do...while`, `while`, and `for` statements.

## PHP

- Align parameter names inside PHPDoc blocks.
- Align PHPDoc comments.
- Insert a blank line before the PHPDoc tag section.
- Insert blank lines around PHPDoc parameter tags.
- Use lowercase `true` and `false`.
- Use lowercase `null`.
- Write `else if`, not `elseif`.
- Insert exactly one blank line before a `return` statement.
- Keep opening braces on the same line for block-level elements.
- Write closures with no space before `(`.
- Use spaces around assignments inside `declare(...)`.
- Keep empty methods on one line.
- Keep empty classes on one line.
- Use fully qualified class names in PHPDoc.
- Always wrap grouped `use` import lists.
- Always wrap PHP attributes.
- Do not preserve existing line breaks during reformatting.
- Do not keep blank lines in declarations.
- Do not leave blank lines immediately before `}`.
- Place class opening braces at the end of the declaration line.
- Place method opening braces at the end of the declaration line.
- Put `else`, `while`, `catch`, and `finally` on a new line.
- Use no space before the `(` in `if`, `while`, `for`, `catch`, and `switch`.
- Always wrap array literals so each element is placed on its own line.
- For multiline array literals, put the opening bracket on its own line.
- For multiline array literals, put the closing bracket on its own line.
- Always force braces for `if`, `do...while`, `while`, and `for` statements.

## JSON

- Do not enforce a maximum JSON line length.
- Do not auto-wrap JSON while typing.
- The only configured JSON visual-guide column is `0`.
