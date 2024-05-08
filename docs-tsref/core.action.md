<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@genkit-ai/core](./core.md) &gt; [Action](./core.action.md)

## Action type

**Signature:**

```typescript
export type Action<I extends z.ZodTypeAny = z.ZodTypeAny, O extends z.ZodTypeAny = z.ZodTypeAny, M extends Record<string, any> = Record<string, any>> = ((input: z.infer<I>) => Promise<z.infer<O>>) & {
    __action: ActionMetadata<I, O, M>;
};
```
**References:** [ActionMetadata](./core.actionmetadata.md)
