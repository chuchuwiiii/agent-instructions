# Comments

Default to no comments. Write one only if a competent engineer reading cold would be confused without it. Max 125 words.

| Rule                                      | Bad                                     | Good                                                      |
| ----------------------------------------- | --------------------------------------- | --------------------------------------------------------- |
| Rename instead of explaining WHAT         | `function check(u, p) // can edit?`     | `function canUserEditPost(user, post)`                    |
| No changelog / diff comments              | `// Added retry logic`                  | No comment, the diff shows it                             |
| No comments on self-explaining constants  | `const MAX_RETRIES = 3; // max retries` | `const TIMEOUT_MS = 5000; // Gateway kills idle at 6s`    |
| No comments on idiomatic code             | `// loop over users`                    | No comment                                                |
| No decorative section headers             | `// ==== Helpers ====`                  | Split the file                                            |
| Don't comment a line just because you touched it | —                                | —                                                         |

Only three cases justify a comment:

| Case                                     | Form                                        |
| ---------------------------------------- | ------------------------------------------- |
| Non-obvious WHY (business rule, workaround) | Inline `// why`                          |
| Constraint spanning lines (rate limits, ordering) | Block `/* ... */`                  |
| Exported API                             | JSDoc: 1-line summary, `@param`, `@returns`, `@throws` |
