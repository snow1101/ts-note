# ts-note

```typescript
function getValue<T extends object, K extends keyof T>(o: T, name: K): T[K] {
  return o[name]
}
```
