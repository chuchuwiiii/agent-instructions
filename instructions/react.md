# React / JSX / TSX

| Rule               | Do                                                                | Don't                                            |
| ------------------ | ----------------------------------------------------------------- | ------------------------------------------------ |
| Preferred stack    | Tanstack Start, shadcn, Tanstack Query, Zustand                   | —                                                |
| Special characters | `<p>{"Don't use this"}</p>`                                       | `<p>Don&apos;t use this</p>` (any HTML entity)   |
| Shared data        | Read from Zustand / Context / hook in the component that needs it | Prop drilling `user` through `App → … → Profile` |
| File names         | `user-profile.tsx` (kebab-case)                                   | `UserProfile.tsx`                                |
| Conditional render | `{isActive && <UserProfile />}`                                   | `isActive ? <UserProfile /> : null`              |
| Related components | Namespace API: `<Card>`, `<Card.Header>`, `<Card.Content>`        | Separate `CardHeader`, `CardContent` exports     |

```TSX
export const Card = Object.assign(CardRoot, { Header: CardHeader, Content: CardContent });
```
