<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@genkit-ai/ai](./ai.md) &gt; [RetrieverAction](./ai.retrieveraction.md)

## RetrieverAction type

**Signature:**

```typescript
export type RetrieverAction<CustomOptions extends z.ZodTypeAny = z.ZodTypeAny> = Action<typeof RetrieverRequestSchema, typeof RetrieverResponseSchema, {
    model: RetrieverInfo;
}> & {
    __configSchema?: CustomOptions;
};
```
**References:** [Action](./core.action.md)<!-- -->, [RetrieverInfo](./ai.retrieverinfo.md)
