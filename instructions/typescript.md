# TypeScript

| Rule                   | Do                                                               | Don't                                             |
| ---------------------- | ---------------------------------------------------------------- | ------------------------------------------------- |
| Preferred packages     | `drizzle-orm`, `better-auth`, `date-fns`, `zod` (when installed) | Hand-rolled ORM, auth, or calendar logic          |
| Types                  | `type User = z.infer<typeof UserSchema>`                         | Standalone `type` / `interface`                   |
| Unclear property names | `status: z.enum([...]).describe("Whether the user can log in")`  | `// whether the user can log in` comment          |
| Ternary length         | `const status = user.isActive ? "active" : "inactive"`           | Ternary wrapping long `await` calls → use if-else |
| Constants              | `IMAGE_DIMENSION = { WIDTH: 600, HEIGHT: 400 }`                  | `IMAGE_WIDTH = 600; IMAGE_HEIGHT = 400`           |
