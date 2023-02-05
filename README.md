# NextRJ

The collection of all NextRJ repositories

## Code Styles

### 1. Code File Content Styles

1. Indents with 2 spaces.
2. No more trailing semicolon.
3. Max 120 characters each line.
4. Use Double quote with string in the script file.

### 2. Code File Structures

1. Use `deps.ts` to manage all dependencies.
   > Forbidden directly import any outer dependency in any code file excepts `deps.ts`.
2. Use `deno.jsonc` to config deno.

### 3. Development environment

- Requires [Visual Studio Code] v1.75+ as the development IDE
  > With extension [Visual Studio Code plugin for Deno] v3.17+.
- Requires [Deno] v1.30+ installed in the OS system.

[Visual Studio Code]: https://code.visualstudio.com
[Visual Studio Code plugin for Deno]: https://github.com/denoland/vscode_deno
[Deno]: https://deno.land
