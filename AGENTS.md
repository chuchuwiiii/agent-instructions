Hi, I'm Chuwong. A Thai dude.

I love building fun software, sometimes corporate. I'm a fullstack software engineer that usually focus more on building a lovable product. This means I love focusing more on the UX/UI rather than complex backend tasks.

I beleive simplicity is the key for programming. Hard problems should be seperated into smaller problems.
I also don't like to read long documentations, or explainations, I would prefer seeing diagrams, or an human-readable bullet summary.

I love to enhance my build every single time.

## Answer format

- Answer concisely in list format, if appropriate.
- When comparing or displaying information, I prefer tabular format.

## Pre-Implementation

- Before any coding task, apply the `andrej-karpathy-skills:karpathy-guidelines` skill.
- Before any coding task, if `.tidy` folder exist, use `chuwong35122:tidy` skill to understand the whole repository and current features before implementing a new one.

## My coding preferences

- Always follow `instructions/comments.md` when writing code.
- I prefer using well-known packages rather than implementing some functions my own (or by you).
- Typesafety is what I want in my code.
- I enjoy ideating on user's experience. Give me option to choose if there is.
- I love small animations. Use `find-animation-opportunities` skill when you are implementing components that require or include visual feedback.
- No Over-Engineering: simplest solution that fits the existing architecture; add complexity only when requirements demand it.
- Reuse, rather than re-create. If there are constants, enums, functions that can be reused, USE THEM.
- NEVER use multiple chaining ternary operator. Only use it once.

## Post verification

- Never kill active port for testing, spin up a new one dedicated for testing instead. Kill the new port once its related tasks are finished.

## GIT

- **IMPORTANT** NEVER commit or push until there is a given instruction
- Use conventional commits pattern (`feat:`, `fix:`, `ref:` etc.) with concise explaination of the implementations
- Use concise single line, max of 2 sentences of commit message.

## Language instructions

Read the matching file only when writing that language:

| Lang              | File                                                           |
| ----------------- | -------------------------------------------------------------- |
| TypeScript        | [`instructions/typescript.md`](instructions/typescript.md)     |
| React / JSX / TSX | [`instructions/react.md`](instructions/react.md)               |
| Comments (any)    | [`instructions/comments.md`](instructions/comments.md)         |

## When to write a spec or implementation plan

- A question is a request for an answer, not for changes. If the message opens with "how hard would it be", "what are your thoughts", "why does", "should we", "is it possible", "can X do Y", or otherwise asks rather than instructs: answer it, and do not edit files.
